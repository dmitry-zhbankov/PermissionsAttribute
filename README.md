# Permissions Attribute
## Short Description
Add custom permissions attribute in ASP.NET Core MVC application.
## Topics
* ASP.NET Core
* WebApi
* Routing
* Model Binding
* Security, Authentication, and Authorization
* Async methods
## Requirements
* If not specified, feel free to choose between .NET Core and .NET Framework technology, but the first one is prefered.
* Remember about code style and naming conventions.
* Hosting application with IIS is welcome but not required.
* Using of the 3rd party libraries that ease the task implementation directly is prohibited.
* Create a simple web app with authorization like this
* Implement ProfileController with several actions:
	* Action that will return one profile by user Id
	* Action that will return a collection of profiles
	* Action that will add user profile to the collection
	* Action that will update user profile in the collection
	* Action that will delete user profile from collection
* Create Permissions enum that will have one separate permission for each Action from (ProfileController. E.g., GetProfileById, GetProfiles etc.
* Create attribute that will check if the authorized user has a permission for the specific Action. E.g. [HasPermission(Permissions.GetProfileById)]
* In case if the user doesn't have the required permission send corresponding error in response.
