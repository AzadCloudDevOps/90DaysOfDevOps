## Task 8 

### What is Git?

- Git is a free and open-source version control system tool used to handle small to very large projects efficiently.

- It is generally used for source code management in software development.

- Git is used to tracking changes in the source code.

- It allows multiple developers to work together. It supports non-linear development through its thousands of parallel branches.

### What is Github?

- GitHub is a web-based platform that provides hosting for version control using Git. It offers all of the distributed version control and source code management (SCM) functionality of Git with its add-on features.

- GitHub is a very popular platform for developers to share and collaborate on projects, and for hosting open-source projects from anywhere.

### What is Version Control? How many types of version controls?

- Version control systems are a category of software tools that helps in recording changes made to files by keeping a track of modifications done in the code. 

- It helps in reverting files to a previous state, reverting the entire project to a previous state, comparing changes over time, seeing who last modified something that might be causing a problem, who introduced an issue and when, and more.

- Types of version controls:

1. A centralized version control system (CVCS): uses a central server to store all the versions of a project's files.

   e.g. Subversion and Perforce.

2. A distributed version control system (DVCS): allows developers to "clone" an entire repository, including the entire version history of the project.

   e.g. Git, Mercurial, and Darcs.

### Why do we prefer distributed version control over centralized version control?

1. Better collaboration

2. Improved speed

3. Greater flexibility

4. Enhanced security
   ![add_text](https://cdn.hashnode.com/res/hashnode/image/upload/v1673211938864/3858015f-310b-4147-b680-4f6aafaa489d.png)

### Tasks
1. Install Git on your local system (if it is not already installed). You can download it from the official website at https://git-scm.com/downloads
   
   ![add_text](https://cdn.hashnode.com/res/hashnode/image/upload/v1673203688918/83a67538-61ea-4eef-8f52-834af9af0520.jpeg)
2. Create a free account on GitHub (if you don't already have one). You can sign up at https://github.com/
   
   ![add_text](https://cdn.hashnode.com/res/hashnode/image/upload/v1673204236858/1e3b3425-daa9-462b-929c-52ea3d34bb79.jpeg)
3. Create a new repository on GitHub and clone it to your local machine
   
   - To create new repository in GitHub, go to  'your repositories' in profile and press ```new``` button on top right corner. This will let you to following page
   
   ![add_text](https://cdn.hashnode.com/res/hashnode/image/upload/v1673212498789/e492a38f-1298-40ed-bb8e-525e7b0130e9.jpeg)
   - Put here your repository name which is unique, add description if you want.
   - Click public so that repo will be accessible to anyone.
   - You can add README File to showcase what's this repo is all about & here is your repo created successfully.
   - Now get inside the repo and press ```add file``` dropdown it and choose create new ```file file.txt``` and ```repo_list.md```
   - Now clone this repository by using command git clone https://github.com/<username>/<repository-name>.git
   
   ![add_text](https://cdn.hashnode.com/res/hashnode/image/upload/v1673209753360/231862c4-d4a4-4146-9b8c-4ee70544f6a2.jpeg)
4. Make some changes to a file in the repository and commit them to the repository using Git 
   Make any changes in files and check the status as below 
   (In this, file listed in red that means it must be added to the repository)
   
   ![add_text](https://cdn.hashnode.com/res/hashnode/image/upload/v1673209643216/87bfef73-a67e-4a4b-af04-8e3af5fe7f99.jpeg)
   
   Now add this changed file & commit this changes to the repository by using ```command git add . && git commit -m "modified the file"Y
   ![add_text](https://cdn.hashnode.com/res/hashnode/image/upload/v1673210459037/1269560b-bce6-41a7-ac28-668e51d4a9c5.jpeg)

5. Push the changes back to the repository on GitHub by using command
   ```git remote add origin <repository-name> && git push origin master```
  ![add_text](https://cdn.hashnode.com/res/hashnode/image/upload/v1673211529733/d1798bab-33da-434c-8482-7e33cf1811a7.jpeg)
  
  Thus if refresh github we can see it gets updated.
  That's all.
  
  Checkout in [Basic Git & GitHub for devops](https://akash-zade.hashnode.dev/basic-git-github-for-devops-engineers-1)
  
