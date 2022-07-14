Multi-Branch-Pipeline-Creation

Multibranch pipoeline: A multibranch job is simply a folder of pipeline jobs. For every branch you have, Jenkins will create a folder. 
So instead of creating a pipeline job for each of the branches you have in a git repository, you could use a multibranch job

Steps to create Multi-branch-pipeline

* Jenkins Dashboard - create new item
* give project name and select multi-branch-pipeline
* add source - select git
* add github url and crednetials
* in github need to create difrent branches like DEV,PROD, QA etc
* source - give jenkins file name-present in the github
* Scan Multibranch Pipeline Triggers- Periodically if not otherwise run- mention time -
if you mention 1min evry 1min jenkins will check the source code in all the branches 
if any updated code jenkins wil automatically triger the build in particular branch.
* apply and save

![image](https://user-images.githubusercontent.com/93968708/178915016-08eed083-7dcb-4671-8880-782322956977.png)

