# Manifests
Use these to deploy the hub and frontend. You can use component specific manifest to deploy only that component or use kube-endoscope.yml to deploy all of them. 
Istio ingress gateway is required. If you want event persistence, you should have a kafka broker reachable by the hub. Provide the details of that kafka broker in hub-deployment.yml or kube-endoscope.yml.

