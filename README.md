# Microsoft-Azure-VM
Creating a virtual machine using Microsoft Azure
Today we are going to create a virtual machine using Microsoft Azure. 

Steps:

1. Make sure you have create a Microsoft Azure Account so that way you can use the portal. Once you have created your account, and if you are having trouble finding the portal, follow this link https://portal.azure.com/
	
2. Once in the portal go to the Azure services and click on Virtual machines.
	
3. Click on add

4. A page loads up that will say at the top, "Create a virtual machine". I currently have a student account set up with Microsoft Azure which also give you $100 o credit to be able to test out some of these services. If you are a student and you have a school email that was given to you by your high school, community college, or university then go to this link https://azure.microsoft.com/en-us/free/students/. If you are a student the click on "activate now" and follow the steps to create a student account. When choosing your project details the users with student accounts will be allowed to choose the Azure for Students subscription.

5. Choose your subscription

6. Create a new resource unless if one is already available.

7. Create a virtual machine name 

8. Choose a recommended region
	a. In this case I chose (US) East US 

9. For Availably option click on availability zone 
	a. Availability zone - 
	An Availability Zone is a high-availability offering that protects your applications and data from datacenter failures. Availability Zones are unique physical locations within an Azure region. Each zone is made up of one or more datacenters equipped with independent power, cooling, and networking. To ensure resiliency, there's a minimum of three separate zones in all enabled regions.
10. For availability  zone click just 1 for this exercise

11. For "Image"  I chose Ubuntu Server 18.04 LTS, but you an just choose which ever one you want. I recommend to just choose the first option.
12. For "Size" option click "Select Size" which is right under the bar that is given. In "Select Size" if you scroll all the way to the right it will show you the cheapest option. During the time I made this the cheapest option was $3.80/month 

13. Next, we will go to administration account.

14. Authentication type: Click SSH public key 
	a. If you choose password you will just have to create a password.

15. Create a username 

16. SSH public key source: choose "Generate new key pair".

17. Create a name for your key pair 

18. Make sure you allow selected ports

19. SSH(22) 
	a. SSH is a secure shell which is a  cryptographic networked protocol for operating networked services securely over an unsecured network. So with this you can connect to this computer remotely using the command line.

20. Now, you make get a caution sign that says, "This will allow all IP addresses to access your virtual machine. Keep in mind this is just for testing and education purposes, but after this you will be able to remove this. 

21. Leave the rest of the tabs alone since this is just for practice and then click on "create + review".

22. Review the basics section to see if everything is ok and then click on "create". 

23. After, it should say you have completed creating your first virtual machine.

24. To see if your  virtual machine is working, click on the link that says, "Run a script inside the virtual machine". This link will be under "Next steps". 

25. Then click on RunShellScript and then you can run a command script 

26. In the first line of the command script type this:
	a. echo "Hello, World"

27. Then click run

28. Give it some time to run and then you should get the output 
	a. Hello, World
		
This will show your virtual machine in action and if that worked then congratulations you have completed creating a virtual machine. 
