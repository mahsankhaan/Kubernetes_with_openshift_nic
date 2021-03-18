# Kubernetes_with_openshift
Let's deploy simple php application on Openshift cluster

## Follow these steps:

## Step 1 : Sign-up for IBM Cloud Platform 

[https://ibm.biz/BdfsdZ](https://ibm.biz/BdfsdZ)

![GitHub Logo](images/s1.png)



## Step 2: Get RedHat OpenShift cluster:
[https://openshiftlab.mybluemix.net]( https://openshiftlab.mybluemix.net)
1. lab_Key:oslab
2. IBM_id: your email 

![GitHub Logo](images/s2.png)



## Step 3: You will see below image once successfully registered

![GitHub Logo](images/s4.png)


## Step 4: Redirected to IBM account and will see external account

![GitHub Logo](images/s5.jpeg)

## Step 5 : Go to resources and the cluster must be there
![GitHub Logo](images/s60.png)

## Step 6: Select the cluster and open web console
![GitHub Logo](images/s7.png)


## Step 7: On web console you will able to see openshift dashboard ,next select create project

### NOTE: Make sure you are under Developer mode

![GitHub Logo](images/s80.png)



## Step 8: Get into newly created project and select Catalog
![GitHub Logo](images/s90.png)


## Step 9: Search for php and select PHP builder image

![GitHub Logo](images/s100.png)


## Step 10: Add Configuration
1. Application name : phpapp
2. Git Repository: [https://github.com/mahsankhaan/Kubernetes_with_openshift_nic.git](https://github.com/mahsankhaan/Kubernetes_with_openshift_nic.git) 

![GitHub Logo](images/s200.png)



## Step 11: Check Build process (Optional)
1. Select Builds from left menu
1. Select the build __phpapp__
1. Under __Builds__,select -> __phpapp-1__  -> logs
![GitHub Logo](images/s110.png)


## Step 12: Access the application
1. Select __Topology__

![GitHub Logo](images/s120.png)


## Step 13: Finally application is running on Openshift
![GitHub Logo](images/s13.png)
