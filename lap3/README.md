## **JENKINS TASK 3**

## **1- what is the benefit of using master-slave architecture rather than building on master only ?**


- ### Jenkins master-slave architecture, also known as Jenkins distributed architecture, allows you to distribute the build and test workload across multiple nodes or agents, which can help you to achieve better scalability, reliability, and performance compared to building everything on the Jenkins master node.



-----

## **2- what is different between authorization and authentication ?**
 ###Authentication is the process of verifying the identity of a user, device, or system. It ensures that the person or system attempting to access a resource is who they claim to be. Authentication is typically achieved by requiring the user to provide some form of credentials, such as a username and password, a smart card, or a biometric factor like a fingerprint or face recognition.

- ### Authorization Authentication is the process of verifying the identity of a user, device, or system. It ensures that the person or system attempting to access a resource is who they claim to be. Authentication is typically achieved by requiring the user to provide some form of credentials, such as a username and password, a smart card, or a biometric factor like a fingerprint or face recognition.
-----

## **3- make jenkins-shared-library and make your jenkinsfile which you used in lab2 to point to this library**
### Pipeline Name

![image](https://github.com/Ashoman/jenkins/assets/40643592/dc44b3d8-21b9-480f-8c0a-e505acb26d7d)

### Global pipeline configuration to point to groovy files on a Repo

![image](https://github.com/Ashoman/jenkins/assets/40643592/69b84349-db24-40ed-94b2-947bcce4d077)

### Pipeline Configuration
![image](https://github.com/Ashoman/jenkins/assets/40643592/d181cafb-493e-43b9-a8f6-c9b92b52c8fd)



### GitHub Repo used for Shared Libraries

![image](https://github.com/Ashoman/jenkins/assets/40643592/43fd7f2f-eb8a-426e-b951-25a7aae8dd81)

### DockerHub Login file in "vars" file

![image](https://github.com/Ashoman/jenkins/assets/40643592/e5bc7eda-6bae-4a5b-b81b-4caf7cf0ca0e)


### Pipeline Output 1

![image](https://github.com/Ashoman/jenkins/assets/40643592/3003e9dc-13ed-4db9-9773-5cbb533b5671)


### Pipeline Output 2

![image](https://github.com/Ashoman/jenkins/assets/40643592/58ef521d-43e8-4f4e-83a3-129ef976b23f)


---
## **4- try to make new slave as container or ec2 server and configure master to use it**
- 


### Running Build on Node
![image](https://github.com/Ashoman/jenkins/assets/40643592/5f5168cb-23d6-4016-9843-ebee50571258)


### Build with slave instance

![image](https://github.com/Ashoman/jenkins/assets/40643592/94aad75c-14ba-42b5-a410-c08b9f2d61b8)


### Build with slave instance (Output 1)

![image](https://github.com/Ashoman/jenkins/assets/40643592/33ca4463-d522-4e50-a381-6016f04b74d1)


### Build with slave instance (Output 2)
![image](https://github.com/Ashoman/jenkins/assets/40643592/53300ef6-30d9-41b4-b131-53363967e446)
