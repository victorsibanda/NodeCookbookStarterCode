# Node Cookbook

This cookbook downloads node, npm, pm2 and Nginx. Which are needed to run an app. In addition the cookbook provisions the setup of Nginx so you don't need to manually configure it. 

## Pre-requisites
- Chef (https://downloads.chef.io/chef-workstation/0.17.5)

## What is Chef

Chef is a configuration management tool which allows you to provision files for installation. Whilst being infrastructure agnostic. Chef allows machine setup on physical machine, in the cloud and virtual machines. Which means all the files will be on the system when you boot it up.

## Installs

- NodeJS
- Nginx
- pm2 and npm

## Commands

### test locally
Unit Test
`chef exex rspec`

Integration Test
`kitchen test`


### Test in AWS
`KITCHEN_YAML=kitchen_cloud.yml kitchen test`
