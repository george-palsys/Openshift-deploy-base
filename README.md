# Openshift-deploy-base
1. Create a pacman project on openshift
`oc apply -f /base/project.yaml`
2. Deploy PVC in pacman project 
`oc apply -f /base/pvc.yaml`
3. Deploy deployment 
`oc apply -f /base/deployment.yaml`
4. Deploy service
`oc apply -f /base/service.yaml`
5. Deploy route
`oc apply -f /base/route.yaml`

