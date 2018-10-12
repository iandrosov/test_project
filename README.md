# Attachment Archive/Download Project


This is an active project demonstrates how to add Salesforce Attachments archive/download functionality to Force.com. This utility has live service running on Heroku, URL: . 
The project also demonstrates how to use Heroku to develop and deploy common services to enhance Force.com solutions. 
Basic functionality provides a web application hosting Java zip archiving service. This service can be used via simple URL from any visual force page or possibly from standard actions. 
Invoking the services with list of Attachment IDs will produce the ZIP file and respond to request with download stream, creating user experience of downloading set of Attachments in a single zip file.
The service also provides SOAP web service interface that will archive Attachments in same manner but instead will save resulting zip file in AWS S3 storage and return download URL to user.

## Getting Started

### Getting an Existing Project
Checkout the remote branch for you project:

    git clone git@github.com:cloudspokes/projects -b cal_services my_project_dir_name

## Quick Working with Git

1. Pull in recent updates: `git fetch`
2. Re-apply your local changes on top of recent fetch: `git rebase`
3. Commit your changes locally: `git commit -m 'Message'`
4. Push you commits up to the repo branch: `git push`

## Reference

It's on the Wiki! [Source Control via Git](https://sites.google.com/a/appirio.com/appirio/Home/Consulting/appirio-centers-of-excellence-coe/coe---application-development/source-control-via-git)
