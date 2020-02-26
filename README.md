# HTML (Email) templates with json content for simple CMS updating

This repo is a clone from https://github.com/ColorlibHQ/email-templates.
I have added (not on all pages as it is a WIP) content example data (in json format) as well as a template.html file.

The objective here is to allow for customized content by easliy updating the relevant content.json file.


I have developed a simple golang application that reads the template and merges the json data to render the final html.

The process will also deploy the resultant html to firebase CDN.

## WIP
The following directories have a template and content.json file.
- /1
- /2
- /3
- /4
- /14
- /20

## Note
refer to the totaljs flow design project for details (in my repo)
