# Rayyan API v1 documentation

Rayyan API v1 is documented using [Insomnia](https://insomnia.rest/) in this repository.
You can access the documentation, as well as debugging examples by installing Insomnia
and linking to this repository.

1. Install Insomnia UI from [here](https://insomnia.rest/download).
1. Clone this repository inside Insomnia using
[this](https://docs.insomnia.rest/insomnia/git-sync) guide.
1. Because this repository is hosted on Azure DevOps (which is not documented in Insomnia),
you will need to generate a personal access token on Azure DevOps using [this](https://docs.microsoft.com/en-us/azure/devops/organizations/accounts/use-personal-access-tokens-to-authenticate) guide. The token scope must have the `Code` permission.
1. Open Insomnia and provide the following in the repository configuration:
    1. URL: https://rayyansys@dev.azure.com/rayyansys/Rayyan/_git/rayyan-api-docs
    1. Username: git
    1. Authentication Token: [your personal access token]
1. You should see all endpoints in the API. Try them one by one and go to any
endpoint and click the `Docs` tab for more information.

Note that you need to
register to Rayyan and get credentials for an API Application before you can use the API.
Contact [Rayyan Support](https://help.rayyan.ai/) for more information.