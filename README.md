<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Azure Crash Course</h1>
This tutorial is a brief crash course in how to create a virtual machine using Microsoft Azure<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop

<h2>What is Azure?</h2>

Azure is a Microsoft cloud computing service. The cloud is a large array of many hundreds of thousands of computers spread all over the globe in data centers. Azure is a a platform that will allow you to rent space in order to store or process your own data. 

Examples of free cloud services include: Gmail, Google Drive, Dropbox, iCloud. 

Paid cloud services such as Azure offer more and varied ways of storing and processing your data. 

Azure offers over 600 services, so you can do almost anything you want using Azure. 

<p>
<img src="https://i.imgur.com/n67WFmt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h1>How is Azure structured?</h1>

Azure divides its resources into Tenants, Subscriptions, Resource Groups, Azure Storage Accounts, 

- The Tenant is representative of your organization 
- A subscription in Azure is a way to separate costs. Think of it as the different departments in your organization which all have their own budgets. The accounting department may have it's own subscription under the Tenant and the Sales department may have another separate subscription. 
- Resource Groups are essentially folders that hold the resources that you create in Azure. 
- Storage Accounts are in their most basic form places to storage your files, but with many additional capabilities, like Google Drive on steroids. 


<h2>High-Level Steps</h2>

- Step 1: Create an Azure account
- Step 2: Create a Resource Group
- Step 3: Create a Storage Account within the Resource Group
- Step 4: Create a Virtual Machine
- Step 5: Login to your Virtual Machine

<h2>Deployment and Configuration Steps</h2>

<h2>Step 1: Create an Azure account</h2>
Go the the official Azure website and create and set up an Azure account using your credit card.

Azure will automatically create a subscription for you. 

So now we have created our Tenant and at least one Subscription.

</p>
<br />

<p>
<img src="https://i.imgur.com/n67WFmt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>


<h2>Step 2: Create a Resource Group</h2>

Once within the Azure Portal, in the search bar at the top, type 'Resource Groups' and click on the option with the same name. 

Click 'Create a Resource Group'. 

Give the Resource Group a name and choose a region that you would like your virtual machine to exist in depending on your needs and click 'Review + Create'. 

</p>
<br />

<p>
<img src="https://i.imgur.com/n67WFmt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<h2>Step 3: Create a Storage Account within the Resource Group</h2>

Return to the search bar, and type 'Storage Accounts'. 

Click on option with the same name. 

Pick a subscription -- make sure to use the Resource Group that we created earlier -- write a globally unique name for your Storage Account, and again choose a region that makes sense for your needs. 

Review and create. Under Storage Account, you can now add containers and this will act as a storage space similar to Google Drive.
</p>
<br />

<p>
<img src="https://i.imgur.com/n67WFmt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<h2>Step 4: Create a Virtual Machine</h2>

Type virtual machines in the search bar.

Click on the option, choose the previously created Resource Group. 

Give your virtual machine a name, add a administrator name and password. 

Choose a image (Operating System) for your virtual machine e.g. Windows 10, and the size (how many CPUs) you need; agree to the licensing, and review and create.
</p>
<br />

<p>
<img src="https://i.imgur.com/n67WFmt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<h2>Step 5: Login to your Virtual Machine</h2>

Search for virtual machines, click on your virtual machine and copy the virtual machine's public IP address. 

Using Microsoft Remote Desktop (download the app if you're using a Mac), add a PC using the IP address copied. 

Click on your virtual machine and login using your administrator username and password created in step 4. 

You have successfully created a virtual machine using Azure! 
</p>
<br />

<p>
<img src="https://i.imgur.com/n67WFmt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  
  <h2>FINISH</h2>
