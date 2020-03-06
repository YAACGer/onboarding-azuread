# Azure AD B2B collaboration

Azure Active Directory business-to-business (Azure AD B2B) collaboration lets your securely share your company's applications and services with guest users from another organization. 
The documentation [here](https://docs.microsoft.com/azure/active-directory/b2b/what-is-b2b) is a good starting point to learn more about Azure AD B2B.

## Add guest users in the portal

If you want to know how you can invite guest users in the Azure Portal have a look at [Quickstart: Add guest users to your directory in the Azure Portal](https://docs.microsoft.com/azure/active-directory/b2b/b2b-quickstart-add-guest-users-portal)

## Add guest users with PowerShell

If you want to know how you can invite guest users with PowerShell have a look at [Quickstart: Add a guest user with PowerShell](https://docs.microsoft.com/azure/active-directory/b2b/b2b-quickstart-invite-powershell)

## restrict access to Azure AD resources for gest users

In many cases you don't want that a guest user can browse your AzureAD resources like users and groups.
[Here](https://docs.microsoft.com/azure/active-directory/fundamentals/users-default-permissions) you can find an overview of the default permissions in Azure AD.

To limit guest user permission got to the Azure Portal, navigate to your Azure Active Directory. Next go to 'Users' -> 'User Settings' and click 'Manage external collaboration settings'. Here you can find all needed settings to limit the guest users permissions.