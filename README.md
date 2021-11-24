# Azure DevOps

## Introduction

I will create an organization in my Azure portal and create a project **joe-project** to work with. It will have a private visibility with a non TFVC version control, therefore I'll use Git. The work item process provides four options, **Basic, Agile, Scrum and CMMI**, I'll grab the basic one which is lightweight and uses simple models. See full [documentation](https://docs.microsoft.com/en-us/azure/devops/boards/work-items/guidance/choose-process?view=azure-devops&tabs=basic-process).

![image-1](./images/image-1.png)

## The Basics

Agile methodology enables an iterative approach which focuses on collaboration, customer feedback and small, rapid releases of software whilst DevOps is considered a practice of bringing development and operations teams together. I need to link my project with GitHub, so I have created a task for that and assigned it to myself, and since I'm doing it now, I have toggled the status to **Doing**. This is handy when working with a team as each person knows what their tasks are and it's easy for management to see who is working on what.

![image-2](./images/image-2.png)

Within GitHub, you can create organizations and in each organization you will have repositories which you can link to your project folder.

![image-3](./images/image-3.png)

GitHub successfully installed in Azure boards.

![image-4](./images/image-4.png)

Back on the board, there is the sprint that was assigned to me and because I have finished it, it needs to be flagged as done. I can also commit and create a pull request to reflect changes on GitHub.

![image-5](./images/image-5.png)

Done with the sprint.

![image-6](./images/image-6.png)

Under boards, the **Query** option enables the Project Manager et al to visualize status and backlogs and make queries of the projects (without any SQL knowledge) using various layers of granularity. They can also select a particular task or sprint and check the progress or read notes on what is happening. Queries can be, emailed, exported as CSV's or even saved for subsequent querying.

![image-7](./images/image-7.png)

Exported query

```csv
ID,Work Item Type,Title,Assigned To,State,Tags
"2","Task","Link GitHub to Azure DevOps Project","Joseph Mwania <josembi@gmail.com>","Done",
```

**Azure Repos** enable collaboration within a team just by providing a cloud-hosted private Git repos and advanced file management just like in GitHub; the only difference between the two been the evident closed projects in Azure as opposed to GitHubs open source.

I have created a new repo for the project and imported it to Azure. I can work with my repo in Azure and even create new repos there and push them to GitHub.

![image-8](./images/image-8.png)
