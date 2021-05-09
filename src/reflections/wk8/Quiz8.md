1. What is the package.json file used for?

It is a file that holds all the data pertaining to the project.


2. At what level of your project do you need package.json when deploying your application? Why?

When you are compiling your code, because if anything in the package.json is missing, the code won't compile.


3. What command will ensure that your Vue code is compiled properly for deployment?

run npm serve


4. _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.

.env files

5. What are the two ways to view the logs from your Heroku app?

The website and your github repository (if it's connected to your Heroku app).


6. How do you update an app already deployed on Heroku?
       1. Create New App  
        2. Open your application
        3.Go to VueConfig on client and change the outputDir.
        4.type '../filename-auth.server/client'
        5. Open terminal, copy/paste above link and type npm run build 
        6. connect it to a github repository via heroku.
        7. Go to Settings, click Reveal Config
        8.Got to your env file, grab all ids and connection string.



7. Why is branching important to version control?

It allows developers on the same team to work on different areas of the project at the same time.

8. When should code review happen?

Before the code is merged into the main branch.


9. What is the term used to define combining two branches?

Merge

