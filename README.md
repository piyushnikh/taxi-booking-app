![image](https://github.com/piyushnikh/taxi-booking-app/assets/91729663/63fbba17-19e9-4473-9303-4db46df09306)

Worked on this sample project which is a real world scenario to work with Git & Github.

Below is the flow for promoting builds from DEV --> PROD which are completed as a part of day to day activities.

1) Setting up local & remote repositories (public/private). Keep code ready on local repository.
2) Creation of separate branches (DEV/UAT/PROD) on remote & local repos.
3) Adding different collaborators for project.
4) Enabling SSH based authentication for developers.
5) Protect Prod & UAT branches by enabling branch protection feature in GitHub.
6) Setting up protection policy, i.e for UAT 1 approval needed & PROD 2 approvals needed.
7) Making sure local & remote repo. heads point to latest commits.
8) Creating a job for testing dry build using maven on Jenkins.
9) If the dry job is successful, create a new PR & deploy code on Tomcat.
10) If build is successful on DEV environment, promote the build to UAT & PROD environment after receiving approvals.

P.S :- This code or any of the files is not written by me, it just shows the process & tasks executed as a part of day to day activities.
