---json
{
    "slug": "create-one-page-website-from-template-[sumolanding]",
    "category": "tutorials",
    "tag": [],
    "layout": "Huong-Dan.html",
    "title": "Create One Page website from template [SumoLanding]",
    "description": "",
    "date": "2016-08-17 17:38:55",
    "featureImage": "https://github.com/easywebhub/sumolanding/blob/gh-pages/img/build-website.png?raw=true"
}
---
#### Summary Information
 + EasyWeb Builder [download here](https://github.com/easywebhub/easyapp/releases/download/2.2/EasyWebBuilder.zip)
 + SumoLanding: a free bootstrap template to build website, free download from [here](https://www.dropbox.com/s/ri1zeijtb5lx58z/SumoLanding.zip?dl=1)
 + Demo website: http://sumolanding.easywebhub.com/  


#### Build a website step by step

**Step 1: Using ```html, css, js``` source from SumoLanding template**

 1. Create new website "SumoLanding" with Standard selection
 2. copy ```/assets/*``` of SumoLanding template into folder ```/asset/assets/*``` (after deleted all old files)
 3. replace ```/layout/index.html``` by ```index.html``` of SumoLanding template 
 4. Build Website and Preview "On Browser" to see local website
![](https://github.com/easywebhub/sumolanding/blob/gh-pages/img/build-website.png?raw=true)

**Step 2: Extract data from layout to data (markdown) file**

 In general, data defined at (index.md) file is binding to corresponding layout (index.html) using HandlebarJS syntax, ```{{variable-name}}``` . Other syntax could be found at Handlebar documentation
 
 1. **Extract and binding data between Layout and Content file**
   + Select ```index.html``` in Layout tab, replace text of ```title``` html tag by ```{{title}}```
   + Change value of ```title``` property in Content Form 
 ![](https://github.com/easywebhub/sumolanding/blob/master/asset/img/binding-data.png?raw=true)
 
   + See the source code of website to see the value of ```title``` is changed
   + Using ```{{{   }}}```, not ```{{ }}``` to escapse ```html``` value of data, e.g ```"Welcome to our new app site.<br/>Sign up now & prepare to enjoy our service."``` of ```header``` property
   
 + **Add other property** (if you want to use Form to edit data): 
   + Define other property, e.g ```"button-text" : "Start your free trial"``` at RAW tab, and binding to layout 
   + Should you json object structure to defined complex data 
 + **Customize display text of Content Form** 
   + Using Config tab to change display text of Property, e.g ```title``` to ```home title```. See the change on Content Form. 
   + Change order of property by drap & drop, see the order of properties are change on Content form
 + Apply the same steps to create website
 
**Step 3: Sync and Deploy to server**
 
 + 1. Requirement
   + Create empty ```github.com``` repository
   + Create domain (or subdomain) and point to that github repo
 + Init github repo and and account in EasyWebBuilder, and ```Refresh``` ,dropdown of ```Build``` button
 ![](https://github.com/easywebhub/sumolanding/blob/gh-pages/img/deploy-github.png?raw=true)
 
 + Synchronize
 + Click ```Set Domain```, dropdown of ```Deploy``` button, and fill domain name, e.g ```sumolanding.easywebhub.com```
 + then Deploy and see website on live domain http://sumolanding.easywebhub.com/