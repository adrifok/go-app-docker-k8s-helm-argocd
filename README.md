Go Web application (go-web-app)


This is a simple website written in Golang. It uses the `net/http` package to serve HTTP requests.
To run the server, execute the following command:
```bash
go run main.go
```
The server will start on port 8080. You can access it by navigating to `http://localhost:8080/courses` in your web browser.



- Containerization (Multi Stage Docker Build) 
- Creating Kubernetes Manifests
- Kubernetes Cluster creation and setup 
- Ingress controller creation, configuration to expose application 
- DNS mapping for our domain (nginx ingress controller)
- Helm chart creation and configuration for multiple environments 

- Continuous Integration using GitHub Actions:

1st stage build and unit test
2nd stage static code analysis
3rd stage Docker image creation and pushing
4th stage  update Helm

- Continuous Delivery using gitOps (Argo CD):

1st stage ArgoCd pulls  helm chart from values.yml 
2nd stage new version is deployed to K8s cluster

- End to End CI/CD demonstration

