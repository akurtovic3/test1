# test1
# Description

Data-Collector-GitHub is a small frontend application implemented using React.js. User authentication is handled using Firebase Authentication and GitHub OAuth application, so the user must log in using an existing GitHub account before fetching data from APIs. The application data is managed using the Redux store. After logging in, user can choose between four menu options:

#### Your Repositories: presents user's private and public repositories: name, private/public, owner, last commit. Users can delete repositories and save changed data as .JSON files. 
#### Starred Repositories: presents user's starred repositories. Users can delete repositories and save changed data as .JSON files. 
#### Add to Starred: users can search for repositories by their title and select them as "starred" or unselect. 
#### Account: presents user's profile, profile photo, and followers. Users can update their profile data and after saving changes, download it as .JSON file. 

# How to run the application?

The application is deployed on Heroku, so you can run it by clicking the link: 

[https://github-data-collector.herokuapp.com](https://github-data-collector.herokuapp.com)

The only thing you need to have is a GitHub account to log in.

#H ow to run the application locally?

After cloning the repository, in the project directory, you can run:

## `npm install`
## npm start
