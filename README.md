# mslearn-ai-vision
Clone the repository for this course
If you have not already cloned mslearn-ai-vision code repository to the environment where you’re working on this lab, follow these steps to do so. Otherwise, open the cloned folder in Visual Studio Code.

Start Visual Studio Code.
Open the palette (SHIFT+CTRL+P) and run a Git: Clone command to clone the https://github.com/MicrosoftLearning/mslearn-ai-vision repository to a local folder (it doesn’t matter which folder).
When the repository has been cloned, open the folder in Visual Studio Code.
Wait while additional files are installed to support the C# code projects in the repo.




Create Custom Vision resources
Before you can train a model, you will need Azure resources for training and prediction. You can create Custom Vision resources for each of these tasks, or you can create a single Azure AI Services resource and use it for either (or both).

In this exercise, you’ll create Custom Vision resources for training and prediction so that you can manage access and costs for these workloads separately.

In a new browser tab, open the Azure portal at https://portal.azure.com, and sign in using the Microsoft account associated with your Azure subscription.
Select the ＋Create a resource button, search for custom vision, and create a Custom Vision resource with the following settings:
Create options: Both
Subscription: Your Azure subscription
Resource group: Choose or create a resource group (if you are using a restricted subscription, you may not have permission to create a new resource group - use the one provided)
Region: Choose any available region
Name: Enter a unique name
Training pricing tier: F0
Prediction pricing tier: F0




Wait for the resources to be created, and then view the deployment details and note that two Custom Vision resources are provisioned; one for training, and another for prediction (evident by the -Prediction suffix). You can view these by navigating to the resource group where you created them.

continues.........https://microsoftlearning.github.io/mslearn-ai-vision/Instructions/Exercises/07-custom-vision-image-classification.html
