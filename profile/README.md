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
  
  - Owners - To be assigned with `Admin` privilages
  - Core - To be assigned with `Maintain` privilages
  - Developers - To be assigned with `Write` privilages
  - Spectators - To be assigned with `Read` privilages

- Individual Access: To give access to any specific users, invite the user to org and add to any of the above team depending on access to be provided
