# Development Guide

- Create a json file (call it content.json)
- Copy the contents below for the schema
- Update the values as needed
- Save the json file in the public/4/ directory **Important**
- In the designer (edit the template module) add the following :-
  -  Label (field)      : 4444he directory of the template we are using)
  -  Reference (field) : name-of-page (i.e MailPage)
  -  Template (field)  : 
  ``` 
    {
      "output": "mail.html" 
      "content": "content.json" 
    }
  ```

## Data schema for public/4/template.html


```
# data schema for public/4/template.html 

{
  "Title":"",
  "TitleDescription":"",
  "TitleUrl":"",
  "TitleBtn":"",
  "Overview":"",
  "OverviewDescription":"",
  "OptionsATitle":"",
  "OptionsA":"",
  "OptionsADescription":"",
  "OptionsAUrl":"",
  "OptionsABtn":"",
  "OptionsBTitle":"",
  "OptionsB":"",
  "OptionsBDescription":"",
  "OptionsBUrl":"",
  "OptionsBBtn":"",
  "OptionsCTitle":"",
  "OptionsC":"",
  "OptionsCDescription":"",
  "OptionsCUrl":"",
  "OptionsCBtn":"",
  "OptionsDTitle":"",
  "OptionsD":"",
  "OptionsDDescription":"",
  "OptionsDBtn":"",
  "OptionsDUrl":"",
  "OptionsETitle":"",
  "OptionsE":"",
  "OptionsEDescription":"",
  "OptionsEUrl":"",
  "OptionsEBtn":"",
  "OptionsFTitle":"",
  "OptionsF":"",
  "OptionsFDescription":"",
  "OptionsFUrl":"",
  "OptionsFBtn":"",
  "AboutDescription":"",
  "Address":"",
  "Phone":"",
  "LinkABtn":"",
  "LinkBBtn":"",
  "LinkCBtn":"",
  "LinkAUrl":"",
  "LinkBUrl":"",
  "LinkCUrl":""
}

```  
## Caveats
The designer will allow you to add as many connections from one node to another.

There is a limitation to (max 3) connections from a node. The evaluator will ignore any connections greater than 3.

**N.B.** The connection URL's will always be in the fields OptionsAUrl, OptionsBUrl, OptionsCUrl.

