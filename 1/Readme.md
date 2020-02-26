# Development Guide

Its important that the designer json file (export from the designer) resides in the public folder


- Create a json file (call it content.json)
- Copy and paste the contents below for the schema into the newly created file
- Update the values as needed
- Save the json file in the public/1/ directory **Important**
- In the designer (edit the template module) add the following :-
  -  Label (field)     : 1 (the directory of the template we are using)
  -  Reference (field) : name-of-page (i.e MailPage)
  -  Template (field)  : 
  ``` 
    {
      "output": "mail.html" 
      "content": "content.json" 
    }
  ```

## Data schema for 1/template.html


```
# data schema for public/1/template.html 

{
  "title": "Test", 
  "titleDescription": "This is a test",
  "titleUrl": "test",
  "titleBtn": "Test",
  "detailDescription": "Another test",
  "overview": "A Test form",
  "overviewDescription": "We are testing",
  "imageOptionsA": "images/001-diet.png",
  "optionsA": "Frist",
  "optionsADescription": "The first test", 
  "imageOptionsB": "images/003-recipe-book.png",
  "optionsB": "Second",
  "optionsBDescription": "The second test",
  "video": "Watch Now",
  "videoDescription": "Its all about testing",
  "contact": "info@test.com",
  "address": "The drive 123223  Test Ave",
  "phone": "1213221312",
  "linkaurl": "#",
  "linkburl": "#",
  "linkcurl": "#",
  "linkabtn": "Home",
  "linkbbtn": "LinkedIn",
  "linkcbtn": "Google+"
}

```  
## Caveats
The designer will allow you to add as many connections from one node to another.

There is a limitation to (max 3) connections from a node. The evaluator will ignore any connections greater than 3.

**N.B.** The connection URL's will always be in the fields OptionsAUrl, OptionsBUrl, OptionsCUrl.

