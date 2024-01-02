# DIGITAL ACCELERATOR @ BANKING

## Cloning the Project Repository

After gaining access to the repositories, follow these steps to clone the required repository to your local machine:

git clone https://github.com/idb-dab/[repository-name].git  
We recommend creating a new branch for any code changes and submitting a pull request against the "development" branch.

## Creating a new repository

A new repository must be created with following guidelines

- Naming: A repository name must be chosen to also logically categorize the repos. for eg:
  - Repo created for a production microservice - `dab-XXXXXX-microservice`
  - Repo created for a production frontend - `dab-XXXXXX-frontend`
  - Repo created for a production microfrontend - `dab-XXXXXX-microfrontend`
  - Repo created for a experimental purpose - `exp-XXXXXX-XXXXXXXX`
  - Repo created for a template project - `template-XXXXXX-XXXXXXXX`
  - Repo created for a production microservice (Digital) - `digital-XXXXXX-microservice`

- Access Groups: When a repository is created, respective teams access has to be assigned for others to be able to use the repos
  
  To do that go to: Repository > Settings > Collaborators and Teams > Add Teams
  
  - `Owners - Admin permissions` - To be assigned with `Admin` privilages (To assign for all repositories)
  - `Core - Maintainer permissions` - To be assigned with `Maintain` privilages (To assign for all repositories)
  - `Developers - Write permissions` - To be assigned with `Write` privilages (To assign for all repositories)
  - `Spectators - Read permissions` - To be assigned with `Read` privilages (To assign for all repositories)
  - `Digital - UI` - To be assigned with required privilages for UI repositories (To assign for all UI repositories)
  - `Digital - Admin Portal` - To be assigned with required privilages for Admin repositories (To assign for all Admin repositories)
(While adding repository permissions you don't need to add child teams)

- Individual Access: To give access to any specific users, invite the user to org and add to any of the above team depending on access to be provided. Please note no member should be given a direct access without adding them to one of the teams in Github.

## Adding a new user to Org

Do not add a user directly to any repository, instead add them to a respective teams which they will be working with - https://github.com/orgs/idb-dab/teams 

- While adding a user
  - Make sure you add the user to the correct team / sub-team.
  - All AEH members should be added to AEH teams, All members with elevated permissions should be added to the parent team.
  - When adding a user, please notify over email to Aaron, Avanish, Dhananjay, Paritosh to avoid any issues with permissions etc.
