# M4 Grading Test Suite

This repository contains a GitHub Actions workflow to run your M4 Team Project Test Specs.  You can then send the results to your instructor and they'll be able to record your grade.

If you're more of a visual learner, there are instructions with images [here](README-visual.md).

## How to Run Your Tests

### 1. Fork the Repository

1. Click the "Fork" button in the top right corner of this page.
2. Change the Owner to your GitHub username.
3. Click "Create fork".

### 2. Run the Action
1. Go to the "Actions" tab in your forked repository.
  - You can click the below badge when you're on your forked repo to navigate to the actions page.
  - [![GitHub Actions](https://img.shields.io/badge/Run%20Your%20Tests-Actions-blue?logo=github)](../../actions)
2. Click "I understand my workflows, go ahead and enable them" if prompted.
3. Select "M4 Team Project Mocha Tests".
4. Click "Run workflow".
5. Enter your Render API URL in the "render_url" input field.
6. Click "Run workflow" again to start the tests.

### 3. View the Results

1. Wait for the workflow to start (it may take a moment).
2. Click on the running workflow to see live results.
3. Once completed, you'll see a summary of passed and failed tests.

### 4. Interpret the Results

- Green checkmarks indicate passed tests.
- Red X marks indicate failed tests.
- You can run the workflow multiple times; results will be appended to previous runs.
- Check out the last section in the [README-visual.md](README-visual.md) file for an example.

### 5. Share the Results

- Send the link to your completed workflow run to your instructor for grading.
- The link should look like: `https://github.com/your-github-username/m4-project-grading/actions/runs/123456789`

## Notes

- You can run the tests multiple times if needed.
- Make sure to use the correct Render API URL for accurate results.
  - Your url should include `/api` just as you would when testing locally.
  - Make sure your Render site is awake.
- The tests suite is run all at once, and then again for individual tests to account for network issues.
  - If you see a test failed in the large group of tests, but passeed in the individual tests, that is okay for passing; just let your instructor know which results to inspect.
