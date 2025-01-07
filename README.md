this repo contians k8's resources to deploy mongodb in to the local minikube cluster, 
storage classes mentioned in the persistent volume claims(pvc mentioned in deployment.yaml) dynamically create persisitent volumes as per the configuration files
mongo compass is the client tool used 
used command " kubectl por-forward svc/mongo-svc 32000:27017 " to use it on local host.

pv and sc has no namespaces attached

for more details about yaml files visit kubernetes homepage
