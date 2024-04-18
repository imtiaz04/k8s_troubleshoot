https://minikube.sigs.k8s.io/docs/start/ based on os use the commands and install minikube on your terminal.

![image](https://github.com/imtiaz04/k8s_troubleshoot/assets/85178565/a760e8ae-b94c-40cd-9d95-139db84bc78e)

can check pods using 'Kubectl get pods' command and check status of minikube

![image](https://github.com/imtiaz04/k8s_troubleshoot/assets/85178565/b86fa718-f294-4a23-9367-f965db8bcbe2)


![image](https://github.com/imtiaz04/k8s_troubleshoot/assets/85178565/af2b036e-e531-4139-830f-59c0d1c709ee)

create one nginx.yml file 

apiVersion: apps/v1
kind: Deployment
metadata:
  name: nginx-deployment
  labels:
    app: nginx
spec:
  replicas: 3
  selector:
    matchLabels:
      app: nginx
  template:
    metadata:
      labels:
        app: nginx
    spec:
      containers:
      - name: nginx
        image: nginx:1.14.2
        ports:
        - containerPort: 80

![image](https://github.com/imtiaz04/k8s_troubleshoot/assets/85178565/132cb74d-3e03-4bae-9e64-b1b7d8313868)


