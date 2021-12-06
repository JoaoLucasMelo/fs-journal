# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
It records important metadata about a project which is required before publishing to NPM, and also defines functional attributes of a project that npm uses to install dependencies, run scripts, and identify the entry point to our package.
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
First level, as its metadata would be available to every level of that project.
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
npm i command.
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
Metadata.
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
Using Heroku logs.
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
Clonning the repository from github, making the changes and commiting to github, setting remote for your project on heroku app and pushing to heroku master to deploy the updates.
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
Using the branches are helpful to make all the updates separately from the original project and them deploying a new version of it and also being able to go back if the new version is not as expected.
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
Code reviews should happen after automated tests have completed successfully, but before the code merges to the repository's mainline branch.
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
Merging.
```