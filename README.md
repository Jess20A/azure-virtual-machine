# azure-virtual-machine
<p align="center">
<img width="234" alt="image" src="https://github.com/Jess20A/azure-virtual-machine/assets/142112890/1ebdc77e-3e8d-4f3a-b3f5-47fe74a60fcf">
</p>

<h1>Creation of a Virtual Machine (Azure)</h1>
This tutorial outlines the steps to successfully create a Virtual Machine using Microsoft Azure.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 10 (22H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Create an Azure Subscription (https://azure.microsoft.com/en-us/free)
- Create New Resource Group
- Create Virtual Machine
- Use Remote Desktop to start up Virtual Machine

<h2>Deployment and Configuration Steps</h2>

<p>
<img width="903" alt="image" src="https://github.com/Jess20A/azure-virtual-machine/assets/142112890/f15ccce3-656f-4c6c-b0d8-f9047e0b5098">
</p>
<p>
Begin by clicking the link (https://azure.microsoft.com/en-us/free), followed by clicking the green "Start Free" box to start creating your account. Keep in mind you will need a credit card in order to create this account, but for 30 days you are given a $200 Azure credit and afterwards you can pay as you use. 
</p>
<br />

<p>
<img width="766" alt="image" src="https://github.com/Jess20A/azure-virtual-machine/assets/142112890/b470af92-a0dc-469f-8c69-644c11913c83">
</p>
<p>
If your account creation was successful this is how your home page will look like and now you can continue to the next steps.
</p>
<br />

<p>
<img width="539" alt="image" src="https://github.com/Jess20A/azure-virtual-machine/assets/142112890/e0d48567-f02b-41e1-af34-39245a60ae79">

<img width="556" alt="image" src="https://github.com/Jess20A/azure-virtual-machine/assets/142112890/585a91e4-d024-41a7-b434-eb853336c3f0">
</p>
<p>
Now you can click on Resource Groups on your home page, follwed by clicking Create. Name your resource group and then for Region I would recommend you to choose (US) West US 3 or (US) West US 2 to avoid having issues. Go ahead and click Review + Create, if you get the green message saying Validation Passed you did everything right and now just click Create at the bottom.
  
</p>
<br />

<img width="527" alt="image" src="https://github.com/Jess20A/azure-virtual-machine/assets/142112890/0ca9ad90-e571-4153-97aa-192f060afc07">\

<img width="611" alt="image" src="https://github.com/Jess20A/azure-virtual-machine/assets/142112890/a5ea18f2-fa5a-467b-aa1e-63523a0833a9">

<img width="578" alt="image" src="https://github.com/Jess20A/azure-virtual-machine/assets/142112890/b1954290-130f-4ec7-b69c-7aa325384fe6">

Going back to your home page click on Virtual Machines > Create and select the first option Azure Virtual Machine. Now you will start off by selecting the resource group you created, naming your virtual machine and selecting the same Region that you just used. For Image select Windows 10 Pro, version 22H2 - x64 Gen2. Fill out the username and password you would like. At the bottom click the Licensing box and then continue to Review + Create. If the Validation Passed click Create. Now wait for the deployment of your Virtual Machine and then on to the next step.

</p>
<p>


<img width="771" alt="image" src="https://github.com/Jess20A/azure-virtual-machine/assets/142112890/51500df4-5c72-47b6-a38e-b4a0ccf2fc45">

After your Virtual Machine Deployment, go to your Azure home page > Virtual Machines and click on the Virtual Machine you just created. Copy your VM's Public IP Address and then search for Remote Desktop Connection on your computers search bar. Once you open Remote Desktop paste the VM's Public IP Address and click connect.



<img width="677" alt="image" src="https://github.com/Jess20A/azure-virtual-machine/assets/142112890/8dccb6c7-11b0-4aec-acc0-8f5ba33f28ef">


<img width="644" alt="image" src="https://github.com/Jess20A/azure-virtual-machine/assets/142112890/2180fd38-c000-4e2b-b60d-aa8f73b63767">
<p>


After connecting with the IP Address, another screen will pop up to have you type in your credentials. Go down to More Choices > Use a Different Account and your username and password will be the same ones you used to create your Virtual Machine. CLick OK and then you will get a message saying the Identity of the Remote Computer cannot be verified just click Yes and now you should have successfully logged into your Virtual Machine.








