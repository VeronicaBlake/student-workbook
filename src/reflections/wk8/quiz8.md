# Deploying Applications

**1.** What is the package.json file used for?

```

the package.json file stores and gives information to npm that allows it to identify the project and anything that might be dependant to the project.

``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?

```

I assume it's at the top level of the application.

```
**3.** What command will ensure that your Vue code is compiled properly for deployment?

```

npm i

```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.

```

.env files

```
**5.** What are the two ways to view the logs from your Heroku app.

```

1."$ heroku logs -n 500"
2."$ heroku logs --tail"

```
**6.** How do you update an app already deployed on Heroku?

```

1. Clone the app onto your local computer 
2. Make the changes, upload to github
3. log in to heroku
4. in the terminal, run "heroku git:remote -a <YOUR PROJECT NAME>"
5. in the terminal "git push heroku master"

```
**7.** Why is branching important to version control?

```

if two people work on the same file at the same time and try to merge, it's going to be a really bad time. branching is the best way to keep track of what changes where made when, and to ensure there is no overlap on the main branch. 

```
**8.** When should code review happen?

```
After automated tests, but before merging into the main branch.

```
**9.** What is the term used to define combining two branches?

```

Merging 

```
