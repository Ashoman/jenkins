
# **Jenkins Task 2**
## **1- What is Jenkins pipeline?**
#### Jenkins pipeline is a process where developers are able to implement and integrate continuous integration pipelines in Jenkins.
<br>

---
<br>
## **2- What scripting language is Jenkins pipeline syntax based on?**

- ### GROOVY
 -----------------
 ## **3- What are the different ways to trigger pipeline?**

- ### SCM Trigger: By monitoring the source code repository.
- ### Manual Trigger: User manually click the button .
- ### Webhook Trigger: Git notify Jenkins when changes occur.
- ### Scheduled Trigger: Define the time of excution .
- ### Parameterized Trigger: By changing the parameter you can change the output .
- ## **4- What is different between parameter and jenkins env variable?**

- ### Parameters in Jenkins are user-defined inputs that allow customization and configuration of a build or pipeline run.
- ### While env variables are predefined variables that are set by the Jenkins environment itself or can be explicitly defined within your pipeline script or job configuration.

-----


## **5- What is organization folder job and what is used for ?**
- ### Track a github organization.
-<br>
## **6- Create jenkins pipeline for your repo and use script file (jenkinsfile) to write pipeline syntax, include parameter functions and env variable in it**

### Pipline
![image](https://github.com/Ashoman/jenkins/assets/40643592/a34090b3-0617-42da-b8a8-7096d380fdf8)

<br><br>

### cresentials used to access GitHub Repo
![image](https://github.com/Ashoman/jenkins/assets/40643592/e291747e-e03e-46d7-b588-09fe5cc6b4d7)


<br><br>

### File that will used to find and build
![image](https://github.com/Ashoman/jenkins/assets/40643592/a3307244-7bff-4b12-9339-f974e4d93b06)

<br><br>

### jenkinsfile script
![image](https://github.com/Ashoman/jenkins/assets/40643592/52a3b74d-109a-4e0a-b326-20a4edf85442)

<br><br>

### build performed
![image](https://github.com/Ashoman/jenkins/assets/40643592/d1f30b09-acce-453b-bbce-4f2021931e65)

<br><br>

### Output-1
![image](https://github.com/Ashoman/jenkins/assets/40643592/e270c8df-254e-4218-9a94-e467fab4b28e)

<br><br>

### Output-2 (cont)
![image](https://github.com/Ashoman/jenkins/assets/40643592/91d265d7-0bf5-45a8-814a-3a7d7865590e)

<br><br>

### Output-3 (cont)
![image](https://github.com/Ashoman/jenkins/assets/40643592/cd5db8bb-b8b1-4ffb-b778-957d5b423a6b)


---
<br>

---
<br><br>
## **7- Create another multibranch pipeline and filter branches to contain only (master , dev , test )**


*****
### Pipline name (mutli-branch)
![image](https://github.com/Ashoman/jenkins/assets/40643592/0b136895-e3d1-4330-b8bc-70fe362275bf)

<br><br>

### multi-branch config
![image](https://github.com/Ashoman/jenkins/assets/40643592/35e030fd-6d82-40e4-aef4-5921471d9788)


<br><br>

### detect specific branches on GitHub
![image](https://github.com/Ashoman/jenkins/assets/40643592/f6ec44be-e764-4150-99c1-fb08d28b7ef8)

<br><br>

### Showing detected branches
![image](https://github.com/Ashoman/jenkins/assets/40643592/6836421f-f399-4bcc-9956-66c33d77203d)

<br><br>

### Branches available on Github
![image](https://github.com/Ashoman/jenkins/assets/40643592/454f1608-2f45-460e-871e-e2df7cc6c16f)

<br><br>

### dev-build "build"
![image](https://github.com/Ashoman/jenkins/assets/40643592/b4f90ef4-465f-48aa-b46c-a20f71fd9dd3)

<br><br>

### stage-build "build"
![image](https://github.com/Ashoman/jenkins/assets/40643592/5b965d1c-dbd3-4d9f-9195-02fa3094737b)

<br><br>
### test-build "build"
![image](https://github.com/Ashoman/jenkins/assets/40643592/3f551ac0-a20a-4b7d-b983-3d250da471bb)
