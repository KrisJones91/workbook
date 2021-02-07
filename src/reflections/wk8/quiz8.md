# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
It's a file where all packages are stored to manage and maintain all the pacakges/dependencies of your project. It gathers other peoples code so you can improve your codes functionality while also showing the versions of the your projects dependencies. 
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
On the outermost layer because your application is dependent on the metadata being held within the file.
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
vue-cli
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
.env file in the server and authconfig in the client
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
By logging into your Heroku dashboard, choose the app, click more and view logs. Or you can use the command line to fetch the apps most recent logs, "$ heroku log"
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
Open the project, git init, add the origin url with remote, pull the latest version from github, commit all the changes and push everything to Heroku.
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
It's important to separate in-progress work from tested/already working code
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
Before merging the code to the main branch
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
Merge or integration
```
