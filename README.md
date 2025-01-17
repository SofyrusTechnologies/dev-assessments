# GetQuorum Developer Assessments

Congratulations!

If you've made it this far then you're an awesome candidate. The next step is for you to complete an assessment of your technical abilities. The assessment only requires basic JavaScript knowledge and can be completed in around 30 minutes to an hour. Once you are done submit the zipped solution. It's an opportunity for you to assess how we collabrate as a dev team as well.


## Getting Set Up

The assessment requires NodeJS to be installed in your dev environment. If you do not have NodeJS installed we suggest using [nvm](https://github.com/nvm-sh/nvm) to install the latest version.

1. Clone this repo
3. Run `npm install` to install the dependencies

You'll be all setup now.

## Instructions

Go into the folders to find the instructions for each test.  There are currently

> 2 test(s)



## Submitting the Assessment
 Make a zip file of the cloned and completed solution and then share the zip over email and skype
- to: contact[AT]sofyrus.com (replace the [AT] with @)
- subject: "Dev Assessment for [Your Name]" _(replace [Your Name] with your name)_

NOTE: Make sure the repo is publically available. 


## How we check your solution

1. We'll run the test suite to ensure that all tests pass. 
2. We'll take a look at your code and do a code review with you

### The Test Suite

In order to ensure that your solutions are correct, each test will have a `*.spec.js` file that defines the passing conditions. 

You can run the test suite using the following command from the project root:

```bash
# Check that all tests have passed:
$: npm test
```

If the tests pass, you'll see something like the following in your terminal:

```
jj@DESKTOP-FTJVLMP:~/dev/sofyrus/dev-assessments$ npm test

> dev-assessments@1.0.0 test /home/jj/dev/sofyrus/dev-assessments
> mocha **/*.spec.js



  Test 1 - Simple Example
    ✓ Results should match expected_output.json


  1 passing (6ms)
```

If it fails, you'll see something like:

```
jj@DESKTOP-FTJVLMP:~/dev/sofyrus/dev-assessments$ npm test

> dev-assessments@1.0.0 test /home/jj/dev/sofyrus/dev-assessments
> mocha **/*.spec.js



  Test 1 - Simple Example
    1) Results should match expected_output.json


  0 passing (6ms)
  1 failing

  1) Test 1 - Simple Example
       Results should match expected_output.json:
     AssertionError: expected undefined to deeply equal [ Array(10) ]
      at Context.it (test_1/index.spec.js:12:33)



npm ERR! Test failed.  See above for more details.
```

Be sure to We recommend looking at the spec file to get a better understanding of what we're looking for.

### The Code Review

We will call you remotely by video chat, we'll do a code review with you. We'll ask you questions about why you chose a particular solution to each test. We may also ask you to modify the code to solve another problem. 

## Let's Get Started!
