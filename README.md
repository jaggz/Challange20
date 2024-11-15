# CI/CD Tutorial


## Description

- AS A software engineer we have integrated a CI/CD pipeline in a codebase.
- A full-stack application that runs test cases when a Pull Request is made to the develop branch and automatically deploys to Render when the code is merged to main
- SO THAT we can ensure that all code integrations are clean and pass the proper requirements and that the application is constantly updated when major releases are made to the main branch

## Instructions

- GIVEN a full-stack application Deployed on Render : `https://challange20.onrender.com`
- Use `cypress_test.yml` and `deploy_to_render.yml` files and place in the folder `.github/workflows/` to initiate Git Hub Actions 
- WHEN we upload new features to the application
- THEN we should be making Pull Requests to a develop branch first
- WHEN we create a Pull Request to a develop branch
- THEN we should be executing a GitHub Action that checks the Cypress component tests and End To End Test
- WHEN we see that the tests pass on GitHub Action
- THEN we should see those test results on GitHub Action and merge the code
- WHEN we push the code from the develop branch to the main branch.
- THEN we should see that another GitHub Action triggers and should automatically deploy to Render

## 🏆 Technologies

- `CI/CD Pipeline`
    - `Cypress Component Testing`
    - `Cypress E2E Testing`
- `GitHub Actions`
    - `cypress_test.yml`
    - `deploy_to_render.yml`


## license 
- ![MIT license](https://img.shields.io/badge/license-MIT-blue.svg)
## Questions 
- ![GitHub Username](https://img.shields.io/badge/GitHub_Username_:-@Jaggz-green)
- ![GitHub Email](https://img.shields.io/badge/Email_:-js.dohil@gmail.com-yellow)
- ![Render WebPage Link](https://img.shields.io/badge/Render_Link_:-8A2BE2): https://challange20.onrender.com


