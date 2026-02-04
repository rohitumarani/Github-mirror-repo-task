# **Git and Gitlab assignment**
### **Main Task: GitHub & GitLab Collaboration & Workflow Setup**

You are part of a DevOps team working on two different platforms – GitHub and GitLab. Your team wants to ensure smooth development, proper access control,and repository mirroring between the two platforms.

---
## **Part 2 : GitLab Tasks**
### Subtask 4: GitLab Repository Setup

#### 1. Create a private repository on GitLab.
 - Created On Private Repo On GitLab
![](./img/img1.png)

#### 2. Clone it on your local machine using SSH (not HTTPS).
- Copy The URL SSH URL
![](./img/img2.png)

- Create One Folder Into Local Machine
![](./img/img3.png)


- Use Commond For Clone Private Repo To Local Machine
   ```bash 
   git clone git@gitlab.com:rohitumarani/private-repo.git
   ```
  ![](./img/img4.png)

 - Already Created SSH Key 
 ![](./img/img5.png)
 How to check the Path:
   ```bash 
   C:\Users\DELL\.ssh
   ```
- SSH Key On GitLab
![](./img/img6.png)

#### 3. Create a simple project structure (e.g., src/app.py , docs/guide.md).

- Created Src Folder inside that app.py file
![](./img/img7.png)
- Created docs Folder inside that guide.md file
![](./img/img8.png)

---

### Subtask 5: Repository Mirroring
---
#### Create a mirror setup:
#### 1. Set the GitHub private repo as the mirror of your GitLab repo.

- Created One New Repo On Github For Mirroring
![](./img/img9.png)

- Add This Github Repository to the GitLab Repository
![](./img/img10.png)

- Create Personal Acess Token. It Required For Password Authetication 
![](./img/img11.png)

- After That Paste That Tokenn And Setup Up GitLab and GitHub 
![](./img/img12.png)

#### 2. Push some changes to GitLab and verify if the changes reflect in GitHub automatically.

- Push the Changes 
![](./img/img13.png)
 Use Commond For Push 
   ```bash 
   git push -u origin main
   ```


 
- Check On GitLab Changes 
![](./img/img14.png)

- Check On Github Changes
![](./img/img15.png)

---

### Subtask 6: Access Control

---
#### Invite your friend to the GitLab private repository:

- Invite Member to the Repository
![](./img/img16.png)
- Assign them the Guest role initially, observe the access.
![](./img/img17.png)

- Then change their role to Developer, and let them push one file.
![](./img/img18.png)
Role is Change To the Devolper
![](./img/img19.png)

---

