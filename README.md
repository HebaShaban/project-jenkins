# Jenkins Task 2 - Configuring Pipeline and Multibranch Pipeline
# 1)What is Jenkins pipeline?

is a suite of plugins that supports implementing and integrating continuous delivery pipelines into Jenkins. This allows you to automate the process of getting software from version control through to your users and customers

# 2) What scripting language is Jenkins pipeline syntax based on?
Jenkins Pipeline syntax is based on the Groovy programm0ing language that branched out java but more simple than it.

# 3) What are the different ways to trigger pipeline?
-Trigger builds remotely.

-Build after other projects are built.

-Build periodically.

-GitHub hook trigger for GITScm polling.

-Poll SCM.


# 4) What is different between parameter and jenkins env variable?
-Above we saw parameters but the main difference between parameters and environment variable is that parameters can be set only to a single project where as environment variable can be set to a one or more projects if it is located in a same source

-Environment variables can be overridden or unset, but params is an immutable Map and cannot be changed. Best practice is to always use params when you need to get a build parameter.

# 5)What is organization folder job and what is used for?
Organization Folders enable Jenkins to monitor an entire GitHub Organization, Bitbucket Team/Project, GitLab organization, or Gitea organization and automatically create new Multibranch Pipelines for repositories which contain branches and pull requests containing a Jenkinsfile.

# 6) Create jenkins pipeline for your repo and use script file (jenkinsfile) to write pipeline syntax, include parameter functions and env variable in it
I used this repository

-Code Links: Jenkinsfile 

-Pipeline git configuration

# ![pipeline](https://github.com/HebaShaban/project-jenkins/assets/128882939/82930f0b-bd43-4173-9cd3-0bb220cfa707)

# ![pipeline2](https://github.com/HebaShaban/project-jenkins/assets/128882939/f08cd79e-711e-4034-8a9b-27f89ccc9955)

# ![pipeline run2](https://github.com/HebaShaban/project-jenkins/assets/128882939/9e30b524-5d27-4e5b-ae10-010695300ff8)

# -Output successfully build

# ![output pipeline](https://github.com/HebaShaban/project-jenkins/assets/128882939/db10011d-cb09-40f8-bff2-de6baa035ad8)
# ![Conf1](https://github.com/HebaShaban/project-jenkins/assets/128882939/9c602c78-bcec-4ec8-bebc-b19a645c6956)
# ![Con2](https://github.com/HebaShaban/project-jenkins/assets/128882939/cc357ee1-bd1d-41ac-8724-b9e6ea6d47a5)

# 7) Create another multibranch pipeline and filter branches to contain only (master , dev , test )?
# -Multibranch git configuration
# ![brache](https://github.com/HebaShaban/project-jenkins/assets/128882939/047cdf86-bab8-4ecb-8b54-469a371601bd)
# ![branch](https://github.com/HebaShaban/project-jenkins/assets/128882939/51972f2b-2e61-4690-824f-65774ef1d63c)
# -scan log
# ![output branch](https://github.com/HebaShaban/project-jenkins/assets/128882939/536af85b-67b0-40a0-bb92-d80554158cec)
# -branch status
# ![run branch](https://github.com/HebaShaban/project-jenkins/assets/128882939/daaa5a60-d68d-48db-99b3-1d3113c42950)


