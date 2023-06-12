# README

To deploy rails and worker,

- `kubectl apply -f deployment.web.yml`
- `kubectl apply -f deployment.worker.yml`
- `kubectl apply -f loadBalancer.yml`


* Images in private ECR registry on AWS.
* DB is RDS postgres instance
* To deploy use EKS AWS cluster
