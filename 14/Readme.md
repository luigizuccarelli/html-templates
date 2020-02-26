# Development Guide

- Create a json file (call it content.json)
- Copy the contents below for the schema
- Update the values as needed
- Save the json file in the public/4/ directory **Important**
- In the designer (edit the template module) add the following :-
  -  Label (field)      : 14 (the directory of the template we are using)
  -  Reference (field) : name-of-page (i.e MailPage)
  -  Template (field)  : 
  ``` 
    {
      "output": "mail.html" 
      "content": "content.json" 
    }
  ```

## Data schema for public/14/template.html


```
# data schema for public/14/template.html 

{
  "Valued": "",
  "ValuedDescription": "",
  "ValuedUrl": "",
  "ValuedBtn": "",
  "Title": "",
  "Title": "",
  "Description": "",
  "NextUrl": "",
  "NextBtn": "",
  "Service": "",
  "ServiceDescription": "",
  "OptionA": "",
  "OptionADescription": "",
  "OptionB": "",
  "OptionBDescription": "",
  "Valued": "",
  "ValuedDescription": "",
  "ValuedUrl": "",
  "ValuedBtn": "",
  "SubOption": "",
  "SubOptionDescription": "",
  "SubOptionAUrl": "",
  "SubOptionABtn": "",
  "SubOptionADescription": "",
  "SubOptionBUrl": "",
  "SubOptionBBtn": "",
  "SubOptionBDescription": "",
  "SubOptionCUrl": "",
  "SubOptionCBtn": "",
  "SubOptionCDescription": "",
  "SubOptionDUrl": "",
  "SubOptionDBtn": "",
  "SubOptionDDescription": "",
  "DataA": "",
  "DataATitle": "",
  "DataB": "",
  "DataBTitle": "",
  "DataC": "",
  "DataCTitle": "",
  "Pricing": "",
  "PricingDescription": "",
  "PlanA": "",
  "PlanADescription": "",
  "AS": "",
  "AP": "",
  "AM": "",
  "PlanADetails": "",
  "PlanAUrl": "",
  "PlanABtn": "",
  "PlanB": "",
  "PlanBDescription": "",
  "BS": "",
  "BP": "",
  "BM": "",
  "PlanBDetails": "",
  "PlanBUrl": "",
  "PlanBBtn": "",
  "Address": ""
}
```  
## Caveats
The designer will allow you to add as many connections from one node to another.

There is a limitation to (max 3) connections from a node. The evaluator will ignore any connections greater than 3.

**N.B.** The connection URL's will always be in the fields OptionsAUrl, OptionsBUrl, OptionsCUrl.

