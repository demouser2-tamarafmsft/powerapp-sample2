# powerapp-sample2

# Connect your Canvas App to GitHub

You can connect your canvas app to use git version control.

In you app go to:

 - Settings > Upcoming features > Activate git version control
 
 ![image](https://user-images.githubusercontent.com/122024492/210783971-e60ab580-3643-4199-b332-d14c9a954171.png)

 
 Then, connect to your repo indicating
 - Repo URL
 - branch -> for multiple team members, each can have a branch to enable collaboration across the app
 - Directory (i.e. the folder where your app will be stored in the repo). If it does not exists, it will be created for you
 - username
 - GitHub access token (you can generate it by going to your GitHub Settings > Developer Settings > Personal access tokens > Generate  > Paste it in powerapps 
 !! You need to enter your token each time you want to edit the app !! 
 
 
 
After saving, you will see your folder in the repo with all elements.

![image](https://user-images.githubusercontent.com/122024492/210783919-33ccd3c2-6f84-40fc-8007-61ecf7d11ac8.png)

If you are working in a different branch than main, you will see these changes and can create a pull request.



# Use github actions with your power platform solutions

Here, we have two main workflows you can use with your solution 

## Export and branch

You can make changes to your solution, and then trigger a workflow in GitHub which unpacks the solution and creates a new branch. This is helpful for collaboration as it allows for quickly making a PR and viewing the changes made.

<img width="951" alt="image" src="https://user-images.githubusercontent.com/122024492/210789256-de812e09-0de7-4cb5-948d-4a9276ad52b8.png">

## Release solution to production





You can check this [repo](https://github.com/microsoft/powerplatform-actions-lab) for further information.

If you want to learn more about the current available actions, click [here](https://github.com/microsoft/powerplatform-actions) and here for the [documentation](https://learn.microsoft.com/en-us/power-platform/alm/devops-github-actions)



## Summary

![image](https://user-images.githubusercontent.com/122024492/210815577-b239a518-6f4b-4e08-826c-8d82140741d4.png)

