# Edgio delivery CDN Kubernetes Ingress Controller Demo Code

 This is a demo to show the use of the Edgio/Limelight API with the Kubernetes API to create Ingresses on demand based on the Kubernetes configuration

## Pieces needed

* Kuberntes cluster with credentials
* Edgio Legacy Limelight account with credentials
* Api controlled DNS server(s) - this example uses Vultr



## Files in this par of the demo

* pywai-inline-deployment.yaml - yaml file describing a Kubernetes deployment object for the demo
* pywai-inline-service.yaml - yaml file describing a Kubernetes service object for the above deployment
* pywai-edgio-ingress.yaml - yaml file describing a Kubernetes ingress object for use with the Edgio Ingress Controller Demo
* pywai-edgio-ingress2.yaml - yaml file describing a second Kubernetes ingress object for use with the Edgio Ingress Controller Demo
* pywai-edgio-ingress3.yaml - yaml file describing a third Kubernetes ingress object for use with the Edgio Ingress Controller Demo
* pywai-edgio-ingress4.yaml - yaml file describing a fourth Kubernetes ingress object for use with the Edgio Ingress Controller Demo

## Notes

 pywai-inline-deployment.yaml actually contains the python program to be deployed inline in the deployment object.  This is not a normal way to deploy workloads but was done to simplify the demo and keep it all self contained in one repo.
