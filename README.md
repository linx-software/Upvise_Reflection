# Upvise Reflection Integration
Using reflection, you can use DLL's provided by third parties in order to perform their specific integration. As an example, we are integrating with Upvise using their DLL. Upvise is a mobile cloud solution that enables you to sync and share your company data between your mobile devices, your cloud account, and with multiple users in a team. You can read more, and register on www.upvise.com

# Upvise SDK
In order to use the Upvise SDK, you can learn more at https://www.upvise.com/dev/home/gettingstarted.htm. To get the specific DLL you need "" you can get it from their github at https://github.com/tbrethes/UpviseSDK

#Reflection
According to Microsoft: Reflection provides objects (of type Type) that describe assemblies, modules, and types. You can use reflection to dynamically create an instance of a type, bind the type to an existing object, or get the type from an existing object and invoke its methods or access its fields and properties. If you are using attributes in your code, reflection enables you to access them.

In essence, reflection allows you to attach a DLL to your Linx solution, without Linx knowing what's inside of it, and then call functions and types inside of the DLL. 

# Setup

- Install Linx Designer (https://linx.software) and open the solution "UpviseConnect". This solution was built with Linx 5.21.
- You will need to provide the following Settings: "UpviseEmail" and "UpvisePassword".
- Download the SDK from the github link above and extract it on your computer. Then you will need to provide the DLL path in the setting "UpviseDLLPath"

# Functions

In order to connect to Upvise, we have build the following 3 functions.
- PullData: Gets a list of items from the given Upvise table
- PutData: Inserts a new item into the given Upvise table
- UpdateData: Updates a specific record on the Upvise table

Please note you will need to use the data structures as provided on the Upvise documentation.

If you require any assistance with integrating with Upvise, please let us know and we can assist.

