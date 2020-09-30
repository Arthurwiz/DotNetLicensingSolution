# .NET Cloud-Based Software Licensing Solution with SendOwl Connector
.NET Cloud-Based Software Licensing Solution with SendOwl Connector

<img src="https://images.squarespace-cdn.com/content/v1/5b989c06e2ccd197e85cc797/1599680467030-AQDMYN4E07RHSY5FVHTO/ke17ZwdGBToddI8pDm48kFTEgwhRQcX9r3XtU0e50sUUqsxRUqqbr1mOJYKfIPR7LoDQ9mXPOjoJoqy81S2I8N_N4V1vUb5AoIIIbLZhVYxCRW4BPu10St3TBAUQYVKcW7uEhC96WQdj-SwE5EpM0lAopPba9ZX3O0oeNTVSRxdHAmtcci_6bmVLoSDQq_pb/LicensingSystem.jpg?format=1500w" />
<br />
UD’s Complete .NET Cloud-Based Software Licensing Solution is 100% .NET solution build with the latest .NET, which includes the .NET Framework, 4.7.2, .NET Core, Azure Function, and SQL Server. It is made for integrating your software products that are compatible with Windows 7 to Windows 10 32/64-bit clients. You can open the solution with the 100% complete source code written in C# in Visual Studio. The full source code is enclosed. There is NO hidden dependency or a licensing/third party dll that may prevent you from using our licensing solution. 

With a modularized architecture, you can mix and match to fit your requirements by implementing your custom module if needed. You can use the cloud-based licensing system for desktop, UWP, mobile-device, or web application. For the shopping cart experience, you can use your own, but we use SendOwl to take care of the e-commerce transaction. We also include complete source code for communicating with SendOwl API.

ROBUSTNESS AUTHENTICATION SYSTEM

The license system allows quick and easy product registration or activation after product installation. The simple and straight-forward license key authentication occurs in the cloud when the user enters a license key from your software. It prevents the license key from sharing when installing on a second computer. You can also offer a 30-day warranty on your product. If there is a refund, the license will prevent the user from using your product. You can help your users from moving the license key from one computer to another computer in the backend. Hence, the license system not only takes care of licensing management but also able to detect the identity of the user’s computer, which further protects unauthorized uses of your product.

CLOUD-BASED/DEPENDENCY/COSTS

The UD’s licensing system is complete, and it includes the core feature of providing the cloud-based authentication using Azure Function. This serverless cloud service costs you virtually nothing (You can check its price) and without paying a heavy-duty host solution! Best of all, once you have the source code, you have total freedom to implement your cloud solution without spending another dime to other online authentication web services. Many licensing services charge a $50-150 monthly plus an additional fee for each active license.  

AUTHENTICATION/DATABASE

The authentication of the license key occurs in the cloud with Azure function with a secure connection https. You can further secure it with Azure Key Vault feature. Inside the function, you can connect to your database in the cloud or on the premise. Or you can use the low-cost Azure NoSQL database provided in the Azure. The source code includes sample SQL files of creating the table and store procedures, and the data access layer code.

SECURITY/ADVANCED ENCRYPTION

As mentioned earlier, the Azure Function already provides an HTTPS-enabled connection. The license system also provides advanced encryption and decryption methods in the CryptoProvider module. We highly recommend you create your own crypto solution with the public and private key.  You can easily replace this module and implement your own. Our cloud-based licensing solution eliminates the possibilities of using a keygen or an algorithm-based license key cracking method.


LIST OF MODULES
SendOwlConnector Module - This module provides the API connection between the SendOwl system and your license management system. It includes a complete .NET source code to manage your SendOwl integration and manipulation through the SendOwl’s API. Once you supply the API key and API secret from SendOwl, you are good to go. You can do many interactions, including licensing, product search and creation, bundle listing and creation/update, subscription, discount, and many more. 

SoftLicenseAzureFunction Module

This SoftLicense serverless function provides the brokerage process between your software product registration and daily checking, and manages the SendOwl Order backend and communicate with your database solution. We also include a complete SQL source code for creating a table, store procedure, and a complete data access layer in C# code to update the database. 

MySoftwareProduct Module

This module is a desktop form project that simulates your application with .NET Framework 4.7.2, which consists of the Main form and the Registration form that communicates with our cloud API to authenticate the license key from the user’s entry. It implements many functions include the daily check besides the registration function. It also contains detailed comments showing you how you can further implement additional features and code explanations. The module helps you to take care of the product refund issue. Hardware detection is also included with the MachineInfo module, as described below, which prevents piracy. You can create various license modes, such as expiring license or creating an evaluation mode, by adding additional status. You can also implement a usage-based monetization model, which reveals specific program features depending on your user’s purchase version.

Supporting Modules and Projects

CyptoProvider Module - provides necessary encryption and decryption methods.

MachineInfo Module – provides unique information about user’s hardware and detects changes to prevent unauthorized software installation.

Additional Test Projects and Console Project for SendOwlConnector

<p>To learn more: 
<a href="https://www.unitingdigital.com/articles/a-complete-net-cloud-based-software-licensing-solution-with-source-code-for-net-professionals/?github" target="_blank" >.NET SOFTWARE LICENSING SOLUTION</a></p><br>
<p><a href="https://www.unitingdigital.com/" target="_blank">Uniting Digital</a></p>

