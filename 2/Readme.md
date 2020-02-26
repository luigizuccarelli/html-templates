# Development Guide

- Create a json file (call it content.json)
- Copy the contents below for the schema
- Update the values as needed
- Save the json file in the public/2/ directory **Important**
- In the designer (edit the template module) add the following :-
  -  Label (field)      : 2 (the directory of the template we are using)
  -  Reference (field) : name-of-page (i.e MailPage)
  -  Template (field)  : 
  ``` 
    {
      "output": "mail.html" 
      "content": "content.json" 
    }
  ```

## Data schema for public/2/template.html


```
# data schema for public/2/template.html 

{
  "Title":"",
  "Description":"",
  "Service":"",
  "ServiceDescription":"",
  "InfoA":"",
  "InfoADescription":"",
  "InfoB":"",
  "InfoBDescription":"",
  "InfoC":"",
  "InfoCDescription":"",
  "Business":"",
  "BusinessDescription":"",
  "BusinessUrl":"",
  "BusinessBtn":"",
  "Info":"",
  "InfoDescription":"",
  "OptionAUrl":"",
  "OptionABtn":"",
  "OptionBUrl":"",
  "OptionBBtn":"",
  "OptionCUrl":"",
  "OptionCBtn":"",
  "OptionDUrl":"",
  "OptionDBtn":"",
  "DataA":"",
  "DataAInfo":"",
  "DataB":"",
  "DataBInfo":"",
  "DataC":"",
  "DataCInfo":"",
  "SubOption":"",
  "SubOptionDescription":"",
  "SubOptionATitle":"",
  "SubOptionA":"",
  "SubOptionADescription":"",
  "SubOptionAUrl":"",
  "SubOptionABtn":"",
  "SubOptionBTitle":"",
  "SubOptionB":"",
  "SubOptionBDescription":"",
  "SubOptionBUrl":"",
  "SubOptionBBtn":"",
  "FeatureTitle":"",
  "FeatureA":"",
  "FeatureADescription":"",
  "FeatureB":"",
  "FeatureBDescription":"",
  "FeatureC":"",
  "FeatureCDescription":"",
  "Offer":"",
  "OfferDescription":"",
  "NextBtn":"",
  "About":"",
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

