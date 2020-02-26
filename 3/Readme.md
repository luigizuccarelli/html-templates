# Development Guide

- Create a json file (call it content.json)
- Copy the contents below for the schema
- Update the values as needed
- Save the json file in the public/3/ directory **Important**
- In the designer (edit the template module) add the following :-
  -  Label (field)      : 3 (the directory of the template we are using)
  -  Reference (field) : name-of-page (i.e MailPage)
  -  Template (field)  : 
  ``` 
    {
      "output": "mail.html" 
      "content": "content.json" 
    }
  ```

## Data schema for public/3/template.html


```
# data schema for public/3/template.html 

{
  "Title":"",
  "TitleDescription":"",
  "Overview":"",
  "OverviewDescription":"",
  "OptionAUrl":"",
  "OptionABtn":"",
  "OptionA":"",
  "OptionBUrl":"",
  "OptionBBtn":"",
  "OptionB":"",
  "OptionCUrl":"",
  "OptionCBtn":"",
  "OptionC":"",
  "OptionDUrl":"",
  "OptionDBtn":"",
  "OptionD":"",
  "OptionEUrl":"",
  "OptionEBtn":"",
  "OptionE":"",
  "OptionFUrl":"",
  "OptionFBtn":"",
  "OptionF":"",
  "OptionGUrl":"",
  "OptionGBtn":"",
  "OptionG":"",
  "OptionHUrl":"",
  "OptionHBtn":"",
  "OptionH":"",
  "AboutDescription":"",
  "Address":"",
  "Phone":"",
  "Phone":"",
  "LinkAUrl":"",
  "LinkABtn":"",
  "LinkBUrl":"",
  "LinkBBtn":"",
  "LinkCUrl":"",
  "LinkCBtn":""
}

```  
## Caveats
The designer will allow you to add as many connections from one node to another.

There is a limitation to (max 3) connections from a node. The evaluator will ignore any connections greater than 3.

**N.B.** The connection URL's will always be in the fields OptionsAUrl, OptionsBUrl, OptionsCUrl.

