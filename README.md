# Continuous Integration / Continuous Deployment (CI/CD) project

## Application Source Code using React App

*This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## CI/CD Pipeline
* Use Github actions to create a CI/CD pipeline.
* Workflow files are capture under: github-project/.github/workflows/.
* Pushing from VS will update Github repository and update App on Heroku.
 
## Local and Global Host
*For global host by Heroku, please click [here](https://cicd-github-project.herokuapp.com/).
*For local host using Visual Studio (VS), please click here.
#### 1. `git clone https://github.com/NoRicePls/github-project.git`
Enter the following from the project directory terminal:
#### 2. `npm install`
#### 3. `npm start`
#### 4. open [http://localhost:3000](http://localhost:3000) to view it in the browser.
The page will reload if you make edits and you will also see any lint errors in the console.

## Steps 
*For setting up Github actions to create a CI/CD pipeline, please click [here](https://medium.com/@michaelekpang/creating-a-ci-cd-pipeline-using-github-actions-b65bb248edfe).
*For Heroku App hosting, please click [here](https://devcenter.heroku.com/articles/getting-started-with-nodejs#deploy-the-app).

## Thoughts
### Issues faced:
#### 1. Google Cloud Platform (GCP): I was unable to see any responses when trying to use the commands 'git remote add origin https://github.com/github-project.git and mkdir.github/' on Google Cloud Editor. Wasted time trying to figure out why it doesn't work on my laptop. There is a timeout on GCP and the imeout is not prompt on my editor when it is active, cuasing me to continue woring without knowing this was one of the causes. I have finally given up trying to use it for my project. I switched over to Visual Studio (VS) because the local files are usually connected when I am working on them and the commands work too.
 
#### 2. Main or Master branches. I didn't realise that I was not working on the Master branch when I failed to do this command 'git push origin -u master'. Github had an update, we now have Main or Master branches to select from. I have then deleted the Main branch to avoid confusion from Github repository and only work on Master branch for this project.

### What have I learnt from this project?
#### 1. How to use Github Actions to create CI/CD pipeline 
#### 2. How to host App from Heroku.
