# Creating an App Service using Microsoft Azure Portal and GitHub
![AppServiceLogo](img/app-service-logo.png)


---------------------------------------------------------


## Requirements
- Microsoft Azure Account ( with funds or credits    )
- Microsoft Azure Suscription
- GitHub Account
- A web browser
- Basic experience with the command line
- Git installed on your system

---------------------------------------------------------

## Instructions
#### 1. Login to the [Azure Portal](https://portal.azure.com/).
#### 2. Once your on the portal's home page, you will see something like this:
![PortalImage](img/portal-main.png)
#### 3. Inside the search bar (located at the top), look for *App Services* and click on it.
![Searchbar](img/searchbar.png)
#### 4. Click on *Create*.
![CreateAppService](img/create-app-service-button.png)
#### 5. You will now have to configure the project details: select your suscription and resource group, in my case, I am creating a new resource group.
![ProjectDetails](img/project-details.png)
#### 6. Now, configure the instance details. I will be providing you with PHP code, so please set the runtime stack  as *PHP 8.0*.
![InstanceDetails](img/instance-details.png)
#### 7. You can now configure the App Service Plan, however, I'll be using the free one because during this practice I won't be deploying a permanent page.
![AppServicePlan](img/app-service-plan.png)
![PricingTiers](img/pricing-tiers.png)
#### 8. If you don't want to configure anything else, click on *Review + Create*.
![ReviewAndCreate](img/review-and-create.png)
#### 9. If validation passed, click *Create*.
![Create](img/create.png)
#### 10. Deployment will begin, please wait a couple of seconds until it's completed.
![DeploymentInProgress](img/deployment-progress.png)
![DeploymentComplete](img/deployment-complete.png)
#### 11. Go to GitHub and download the folder *web-page* that's located inside this repository, you can clone the repository or just download it as a zip file and extract it.
#### 12. Go back to the [main GitHub page](https://github.com/)
#### 13. Create a new repository.
![NewRepo](img/new-repository.png)
#### 14. Now, configure the details of your repository. You will only really need to configure it's name, the rest of the repository details are optional. When you're done, just click *Create repository*.
![RepoDetails](img/repo-details.png)
#### 15. Open your command line or terminal and navigate to wherever you downloaded the *web-page* folder.
![NavigatingInTerminal](img/cd.png)
#### 16. Copy the following commands into your terminal:
> git init
> git add .
> git commit -m "Initial commit"
#### 17. Now, go to your new GitHub repository and copy the commands inside the "*…or push an existing repository from the command line*" section and execute them in your terminal
![GitHubCommands](img/github-commands.png)
#### 18. If you did everything correctly, when you reload your GitHub repository page, you'll see all o the folder's files.
![UpdatedRepo](img/updated-repo.png)
#### 19. Go back to the Azure Portal and go to your new App Service's dashboard by clicking *Go to Resource*.
![GoToResource](img/go-to-resource.png)
#### 20. Inside the dashboard, click on *Deployment center*.
![DeploymentCenter](img/deployment-center.png)
#### 21. Select *GitHub* from the dropdown container.
![Source](img/source.png)
#### 22. If needed, login to your GitHub account.
#### 23. Now, configure the GitHub details.
![GitHubDetails](img/github-details.png)
#### 24. Click on *Save* and wait for deployment to be completed.
![SaveButton](img/save.png)
#### 25. Go to your GitHub repository and reload the page.
#### 26. Click on *Actions*.
![Actions](img/actions.png)
#### 27. You will see the status of your GitHub deployment, if you were quick enough you may see that it is still in progress, please wait until it completes and looks something like this:
![GitHubDeploymentStatus](img/github-deployment.png)
#### 28. Click on the text at the right side of the checkmark (*Add or update the Azure...*).
#### 29. Once you're inside, click on your website's URL.
![GitHubDeploymentComplete](img/github-deployment-complete.png)
#### 30. You are now on your deployed page! Congratulations!
![DeployedPage](img/deployed-page.png)

---------------------------------------------------------

## Congratulations ! You've just made deployed your first App Service using the Azure Portal and GitHub !