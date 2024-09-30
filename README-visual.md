# M4 Grading Test Suite

You can use the GitHub Actions workflow to run your tests and send a link to the results to your Instructor.

[![GitHub Actions](https://img.shields.io/badge/Run%20Your%20Tests-Actions-blue?logo=github)](../../actions)


## Detailed Guide with Pictures

### Fork the Repo

Click the "fork" button in the top right corner of this page.
<br />

![fork-repo](./readme-snippets/image.png)
<br />

Change the Owner to your GitHub username, and then click "Create fork".
<br />

![create-new-fork](./readme-snippets/image-1.png)
<br />

Here's what it'll look like when you've forked the repo:
<br />

![Forked repo](./readme-snippets/image-2.png)
<br />

### Run the Action

You can access the action by clicking the "Actions" tab or "Run Your Tests" button.
<br />

![alt text](./readme-snippets/image-3.png)
<br />

Click the "I understand my workflows, go ahead and enable them" button.
<br />

![Accept workflows](./readme-snippets/image-4.png)
<br />


Click "M4 Team Project Mocha Tests"
<br />

![alt text](./readme-snippets/image-5.png)

<br />

And then click "Run Workflow"
<br />

![alt text](./readme-snippets/image-6.png)
<br />


Add your Render API URL to the "render_url" input, and click "Run Workflow"
<br />

![run-workflow](./readme-snippets/image-7.png)

<br />

It will take a moment to start the tests, but then you'll see the tests running.

<br />

![alt text](./readme-snippets/image-8.png)
<br />


Click in to see the live results.
<br />

![alt text](./readme-snippets/image-9.png)
<br />

<br />

![alt text](./readme-snippets/image-10.png)
<br />

Here's what you'll see when the tests are done:
<br />

![alt text](./readme-snippets/image-11.png)
<br />

## How to Interpret the Results 🌟

You can run the workflow multiple times, and the results will be appended to the end of the previous results.

The results will look something like this:
<br />

![final result](./readme-snippets/image-12.png)
<br />

The green checkmark means the test passed, and the red X means the test failed.

## An X doesn't necessarily mean the tests failed

The tests are run all at once, and then again for individual tests to account for network issues.

If you see a test failed in the large group of tests, but passed in the individual tests or vice versa, that is okay for passing; just let your instructor know which results to inspect.
<br />

### Example Passing Result with Failed Individual Tests

Here is an example where the large suite of tests passed, but one of the individual tests failed.  This is a passing result.
<br />

![still passing despite failed tests](./readme-snippets/image-13.png)
