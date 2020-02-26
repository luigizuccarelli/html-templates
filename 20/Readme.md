# Development Guide

- Create a json file (call it content.json)
- Copy the contents below for the schema
- Update the values as needed
- Save the json file in the public/20/ directory **Important**
- In the designer (edit the template module) add the following :-
  -  Label (field)      : 20 (the directory of the template we are using)
  -  Reference (field) : name-of-page (i.e MailPage)
  -  Template (field)  : 
  ``` 
    {
      "output": "mail.html" 
      "content": "content.json" 
    }
  ```

## Data schema for public/20/template.html


```
# data schema for public/20/template.html 

{
  "Title":"",
  "Alt":"",
  "TitleUrl":"",
  "TitleBtn":"",
  "Info":"",
  "InfoDescription":"",
  "Service":"",
  "ServiceDescription":"",
  "OptionsA":"",
  "OptionsADescription":"",
  "OptionsAUrl":"",
  "OptionsABtn":"",
  "OptionsB":"",
  "OptionsBDescription":"",
  "OptionsBBtn":"",
  "OptionsC":"",
  "OptionsCDescription":"",
  "OptionsCUrl":"",
  "OptionsCBtn":"",
  "OptionsD":"",
  "OptionsDDescription":"",
  "OptionsDUrl":"",
  "optionsDBtn":"",
  "DataA":"",
  "DataATitle":"",
  "DataB":"",
  "DataBTitle":"",
  "DataC":"",
  "DataCTitle":"",
  "SubOption":"",
  "SubOptionDescription":"",
  "SubOptionA":"",
  "SubOptionATitle":"",
  "SubOptionADescription":"",
  "SubOptionB":"",
  "SubOptionBTitle":"",
  "SubOptionBDescription":"",
  "SubOptionC":"",
  "SubOptionCTitle":"",
  "SubOptionCDescription":"",
  "InfoA":"",
  "InfoADescription":"",
  "InfoB":"",
  "InfoBDescription":"",
  "InfoB":"",
  "InfoBDescription":"",
  "AboutDescription":"",
  "Address":"",
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

