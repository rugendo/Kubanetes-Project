# Kubernetes Deployment
### The project uses the kubernete deployment module. This gives kubernetes the control on how to manage traffic flow among the pods used in the project. The StatefulSets gives the programmer the power to do traffic distribution among the pods. Since this is a small project, we choose to use deployment module and avoid SatefulSets for easier deployement and execution of the project.

## The project has two deployment.yaml file. One for the frontend  and the second one for backend. Then we plan to use Secrets and Services and loadbalancer in the project.
