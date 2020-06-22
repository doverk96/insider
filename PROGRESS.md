# Insider

This repository contains DevOps assignment

We have a short assignment we would like to share with you. Please find below.

- Write a simple Kubernetes manifest to expose a nodejs server with the following config:
- There should be 10 replicas running. - Done
- The deployment should autoscale at average 50% cpu and 60% memory. - Done
    kubectl autoscale deployment php-apache --cpu-percent=50 --min=1 --max=10
- Use a custom docker image hosted on ECR called nodejs-test:latest (any region). - Done
- Bonus points if you include how to login and pull an image from ECR. - Done
- Expose the app on port 3000 via an EC2 classic load balancer. - Done
- Any change to the deployment should always ensure at least 7 replicas are running at all times. - Done
- Should have higher priority than daemonset pods. - Not Done
- Bonus points if you do the task as code i.e. using terraform or any other configuration language of your choice. - Not Done
- Bonus points if you also load test the application and include the test results in your submission. - Not Done

If you have any doubts, ask them. If you are making any assumptions of the environment do list them out.