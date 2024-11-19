# Salesforce-Object-Prefixes

Within this repo is a json formatted file which contains the KeyPrefix for multiple standard Salesforce sObjects. The prefixes are the first 3 characters of IDs related to Salesforce sObjects and allow you to identify what object an ID is related to.

There are methods for achieving this within Apex, although for external apps and general quick searches this provides an alternative option for identifying Salesforce IDs.

Note: Knowledge Articles have a range of prefixes so if you are using this in an app, you will need to account for this. Here is an example of the formatting within the json for these. The hash can be any number or character.

```
"kA#": {
    "label": "Knowledge Article",
    "name": "KnowledgeArticle"
},
"ka#": {
    "label": "Knowledge Article Version",
    "name": "KnowledgeArticleVersion"
}
```

## Thanks

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.paypal.com/paypalme/geekstewie?country.x=GB&locale.x=en_GB)
