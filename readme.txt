# GitClone-demo1

A demo repository used to test Jenkins Git integration (SCM cloning) as part of a DevOps lab exercise.

## Purpose
This repository is used with a Jenkins Freestyle job named **GitClone** to demonstrate:
- Connecting Jenkins to a GitHub repository
- Cloning source code via the Git plugin
- Verifying the clone through build console output and workspace files

## Usage
1. Jenkins job **GitClone** is configured to pull this repository.
2. On each build, Jenkins clones this repo into its workspace.
3. Console output confirms the checkout was successful.

## Status
Initial commit — created to give the repository a valid HEAD/branch reference for Jenkins SCM polling.
