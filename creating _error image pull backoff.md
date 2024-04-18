https://minikube.sigs.k8s.io/docs/start/ based on os use the commands and install minikube on your terminal.

![image](https://github.com/imtiaz04/k8s_troubleshoot/assets/85178565/a760e8ae-b94c-40cd-9d95-139db84bc78e)

can check pods using 'Kubectl get pods' command and check status of minikube

![image](https://github.com/imtiaz04/k8s_troubleshoot/assets/85178565/b86fa718-f294-4a23-9367-f965db8bcbe2)


![image](https://github.com/imtiaz04/k8s_troubleshoot/assets/85178565/af2b036e-e531-4139-830f-59c0d1c709ee)

create one nginx.yml file 

![image](https://github.com/imtiaz04/k8s_troubleshoot/assets/85178565/1705868e-84d3-48bd-b051-17523ccc67b3)



![image](https://github.com/imtiaz04/k8s_troubleshoot/assets/85178565/132cb74d-3e03-4bae-9e64-b1b7d8313868)

for creating error will modify yml file in containers image name as ngny:1.14.2 then error will appear like @ beginning 'ERRIMAGEPULL' ERROR will appear later it will be 'imagepullBackoff' Error will appear 

![image](https://github.com/imtiaz04/k8s_troubleshoot/assets/85178565/332a0f07-2c3b-42ec-8f86-8c330b1a9fcb)

so in 2 senarios this 'ERRIMGPULL' & 'imagepullBackoff' error will come one is when you provide unknown image/ invalid image name second is when you try to pull image from private repository.

![image](https://github.com/imtiaz04/k8s_troubleshoot/assets/85178565/b541a9bd-a686-4979-a981-11cdbe03f8e3)


![image](https://github.com/imtiaz04/k8s_troubleshoot/assets/85178565/97d5d94f-66f3-4fd8-bba6-c52a566db34d)










