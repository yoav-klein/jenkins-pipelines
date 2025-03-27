# Gradle + Artifactory
---

This example demonstrates building a Gradle library and publishing it to Artifactory

## Prerequisites
In Jenkins - Artifactory plugin installed, and an Artifactory instance named `artifactory` (or change the name in the Jenkinsfile)
In Artifactory - A Maven repository named `my-maven` (or change the name in Jenkinsfile)

## Usage
Create a Job in Jenkins and point it to this Jenkinsfile

Run the job

You'll see the Artifacts in Artifactory