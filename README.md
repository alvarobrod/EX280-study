# EX280-study
My study notes for Red Hat EX280 Certification (Openshift 4.12)

---

Here are some relevant tasks for the Red Hat EX280 Certification Exam.  
So that you know, this project only covers some topics in the exam. I have included exercises
found here for my study purposes.

## Categories Covered In EX280

- Manage OpenShift Container Platform   
    [Challenge](./09-Manage-OpenShift-Container-Platform.md) 
    [Solution](./solutions/09-Manage-OpenShift-Container-Platform-SOLUTION.md) 


- Deploy applications
  applications that can access secrets with key/val accessible via environment variables in pod  
  create app with deployment->add service->expose route (edge)
  create app via deployment
  add service to deployment  
  create route to service (edge?) 

- Manage storage for application configuration and data  create pv->pvc ReadOnlyOnce
 	[Challenge](./06-Manage-storage-for-application-configuration-and-data.md)  
    [Solution](./solutions/06-Manage-storage-for-application-configuration-and-data-SOLUTION.md)  

- Configure applications for reliability  (liveliness probe)
 	[Challenge](./08-Configure-applications-for-reliability.md)  
    [Solution](./solutions/08-Configure-applications-for-reliability-SOLUTION.md)

- Manage authentication and authorization  
 	[Challenge](./01-Manage-authentication-and-authorization.md)  
    [Solution](./solutions/01-Manage-authentication-and-authorization-SOLUTION.md)  

- Configure network security  (edge with cert/key and maybe CA cert?)
 	[Challenge](./07-Configure-service-account-edge-passthoguh-routes.md)  
    [Solution](./solutions/07-Configure-service-accountedge-passthoguh-routes-SOLUTION.md) 

- Enable developer self-service
  create a default project template with a limit range (max-min-default-request)
  make that the default setting when someone creates a new project   
    [Challenge](./02-Enable-developer-self-service.md)  
    [Solution](./solutions/02-Enable-developer-self-service-SOLUTION.md)  
  
- Manage OpenShift operators
    [Challenge](./10-Manage-operators.md)
    [Solution](./solutions/10-Manage-operators-SOLUTION.md)

- Configure application security  (source pod selector with deployment label and added label [name=value]) port access as well
 	[Challenge](./05-Configure-application-security.md)  
    [Solution](./solutions/05-Configure-application-security-SOLUTION.md) 

- Quotas - Resource Limits - Scale - Autoscale  
 	[Challenge](./04-Quotas-Resource-Limits-Scale-Autoscale.md)  
    [Solution](./solutions/04-Quotas-Resource-Limits-Scale-Autoscale-SOLUTION.md)   

- cron jobs in OpenShift  (at a certain time on x day of month) add service account to job?
 	[Challenge](./03-cron-jobs-in-OpenShift.md)  
    [Solution](./solutions/03-cron-jobs-in-OpenShift-SOLUTION.md)   

- Declarative Resource Management (Kustomize)
    [Challenge](./11-Declarative-Resource-Management.md)
    [Solution](./solutions/11-Declarative-Resource-Management-SOLUTION.md)

- Installing a Helm Chart
    [Challenge](./12-Install-Helm-chart.md)
    [Solution](./solutions/12-Install-Helm-chart-SOLUTION.md)

---

## My Lab Environment
My lab environment consists of a mix of Red Hat Code Ready Containers (CRC) and the lab environment provided by DO280R.  

My CRC environment is on OpenShift 4.13, and I found that the procedure for removing the kubeadmin account differs from 4.12 in the DO280 lab environment.  

Although all of these can be run on your CRC environment, the DO280 lab environment has some of the images I use to deploy, as well as NFS, set up ahead of time for testing Persistent Volume Claims (PVC) and some of the certs created for network security exercises. 

---
Topics not covered here that you should still study for  
  
- Install a Helm chart and deploy an app with it 
- associate key/value secret for application
- LimitRanges
- install openshift operators
- Create a default project template file and enable it for all users



