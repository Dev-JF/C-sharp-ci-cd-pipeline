# C-sharp-ci-cd-pipeline

### This is a basic ci/cd pipeline build. It allows me to practice configuring a ci/cd pipeline for C# .net

Goals
- to use this pipeline on an actual .net project (i.e a basic web interface with db interaction)

currently it only contains:

- main.cs, that when changed is analysed for potential securiy vulnerabilities
- index.sln that has this project dependcies - that are initialised

for code analysis codeql is used
for dependencie initialising .net is used

## what is needed

- Azure web app deployment
