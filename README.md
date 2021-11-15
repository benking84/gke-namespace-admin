# New Project Template

This repository contains a template that can be used to provide a user 
with the GKE role container.clusterViewer the admin role on a namespace.

## How to use this 

1. Create a google group for your new namespace
2. Add all the namespace admins to the group
3. Give container.clusterViewer to the group
4. Modify the 2 yaml files to use the correct namespace, and group created above
5. Connect to your GKE cluster
6. Run kubectl apply -f hello-admin-role.yaml
7. Run kubectl apply -f hello-role-binding.yaml