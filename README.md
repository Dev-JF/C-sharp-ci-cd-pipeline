# C-sharp-ci-cd-pipeline

This is a basic ci/cd pipeline build to test and a pipeline build

currently it only contains:

- main.cs, that when changed is analysed for potential securiy vulnerabilities
- index.sln that has its dependcies initalised 

for code analysis codeql is used
for dependencie initialising .net is used

## what is needed

- Azure web app deployment
