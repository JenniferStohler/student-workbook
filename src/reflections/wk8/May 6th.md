##May 6th

<b>What are the three main types of testing we can accomplish in Vue? What does each method provide?</b>

1- Unit: Tests individual units of code. Has an assertion library, which contains error messages that help reduce the time it takes to debug. 
2- Component: Tests Vue components. Component testing libraries need to be as compatible with Vue as possible. Has first class error reporting (and tells you what was expected vs. what was received).
3- End-to-End: Provides coverage on what happens when users use your application. 

<b>What testing method do you think is the most useful? Why?</b>

I think that Component Testing is the most useful. It not only tests every single component, it also tells you what your errors are and what it was expected to be given.

<b>What testing method do you think is the least useful? Why?</b>

While E2E might seem like the most useful, it has the most drawbacks. Running it takes a long time and diminishes returns.