# Microservice-Deploy-in-EKS
#SUCCESSFULLY DEPLOYED MICROSERVICE IN EKS CLUSTER 🙌



![Screenshot (16)](https://github.com/pillakarthik4/Microservice-Deploy-in-EKS/assets/130967802/ce3493c8-9ac0-49ba-99be-53b2c894e7c9)



Deploy Microservices into EKS Using Jenkins Pipeline & Kubectl CLI

DEMO:
-Setup jenkins and install Docker and required Plugins
-Create Cluster using eksctl
-Create jenkins Pipeline  to Deploy Microservice into EKS cluster 
-Verify Deployement using Kubectl
-Access the Microservice app

-----STARTED-----------------
Created Jenkins server installed -Java install 
                                 -Maven
								 -Jenkins
								 -AWS cli
								 -EKS cli
								 -Kubectl
								 -Created IAM Role with Administrartion access and attached to Jenkins Server
								 -Install Docker in ubuntu user (taken duplicate terminal while another terminal is created EKS cluster)
								 -We need to add Add jenkins user to Docker group because jenkins performing the docker 
                                    sudo usermod -a -G docker jenkins
									sudo service jenkins restart
Created ECR for repository
