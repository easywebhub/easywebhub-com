---json
{
    "slug": "how-to-use-easywebbuilder-to-build-websites",
    "category": "tutorials",
    "tag": [],
    "layout": "Huong-Dan.html",
    "title": "How to use EasyWebBuilder to build websites",
    "description": "",
    "date": "2016-08-17 17:42:32",
    "featureImage": "https://github.com/easywebhub/easyapp/blob/master/documents/EasyWebBuilder/preview-on-local.png?raw=true"
}
---
**EasyWebBuilder is a software of easywebhub.com to build, manage and deploy websites with only HTML, CSS basic knowledge.**

##### Setup and run application:
 + Download file from [here](https://github.com/easywebhub/easyapp/releases/download/2.2/EasyWebBuilder.zip)
 + Unzip and click ```EasyBuilder.exe``` to run
 
#### List of features
 1. Create new website
   + Click "Create new site", choose "Standard" and fill the name of your site
  ![create-new-site](https://github.com/easywebhub/easyapp/blob/master/documents/EasyWebBuilder/create-website.png?raw=true)

 1. Preview website on local
   + Click "Build" button to start the website to preview on local
   + Using external browser by click "On Browser"
  ![preview on local](https://github.com/easywebhub/easyapp/blob/master/documents/EasyWebBuilder/preview-on-local.png?raw=true)
 + Edit data in Content Form, then view the change on website
   + Select ```index``` Content which defines the home page of website
   + Change text of ```header``` property, and see the change on browser
  ![edit content](https://github.com/easywebhub/easyapp/blob/master/documents/EasyWebBuilder/edit-content.png?raw=true)
 + Data binding between Content and Layout
   + Click "Layout" button and see the data binding using ```{{ }}``` syntax.

  ![binding data](https://github.com/easywebhub/easyapp/blob/master/documents/EasyWebBuilder/content-layout-binding.png?raw=true)
   + EasyWeb using [HandlebarJS](http://handlebarsjs.com/) framework to binding data between Content and layout. 
   + We could fill data directly to layout and see the change on website
  ![edit layout](https://github.com/easywebhub/easyapp/blob/master/documents/EasyWebBuilder/edit-layout-data.png?raw=true)
   + Click [here](coming soon) for more detail about data binding (coming soon).

 + Add a page (using same layout) and view the created page
   + Click ```Add Content``` to create new page ```home-page``` using the layout of home page of website
   + Change data for some properties in Content Form, e.g ```header, description```
   + Preview new page on local by adding slug to domain, e.g 
     ```http://localhost:3000/home-page/```
 ![create page](https://github.com/easywebhub/easyapp/blob/master/documents/EasyWebBuilder/create-page-home.png?raw=true)
 + Customize text on Content Form in Config
   + select "index" content, click Config tab
   + choose "description" to customize, change ```Display name``` and type ```LongText``` of input text
   + see customization on Content Form
  ![config](https://github.com/easywebhub/easyapp/blob/master/documents/EasyWebBuilder/edit-config.png?raw=true)

 + Edit html code in layout and view the change
   + change background image in Layout from ```bg1.jpg``` thành ```bg2.jpg```, click ```Save``` and see on browser
  ![change background](https://github.com/easywebhub/easyapp/blob/master/documents/EasyWebBuilder/change-background-layout.png?raw=true)
 

 + Add a new Layout and a page used that layout, view created page

 + Init with github account
   + create a new repository on [GitHub](https://github.com) or choose empty repository with write permission
   + Click "Init" on EasyWebBuilder and fill github account
   
 ![github deploy](https://github.com/easywebhub/easyapp/blob/master/documents/EasyWebBuilder/init-github-repo.png?raw=true)
   + **Must "Refresh" the build to continue PreView on local or Sync, Deploy to server**
  ![refresh](https://github.com/easywebhub/easyapp/blob/master/documents/EasyWebBuilder/refresh-build.png?raw=true)

 + Sync on cloud by click ```Sync``` button
 + Deploy and view production website
   + Click ```Deploy``` button
   + After the deployment is completed, see url of github page. This url is your website
![github deploy](https://github.com/easywebhub/easyapp/blob/master/documents/EasyWebBuilder/deploy-github-page.png?raw=true)
 + **GitHub take a while to deploy or update content website, so please wait**
 + **Please use your domain or subdomain for production website**  following github [tutorials](https://help.github.com/articles/using-a-custom-domain-with-github-pages/)

**Github provide subfolder for your website and it make something display on website terrible. So just use ```github.io``` page for ```quick deployment``` and use your sub domain as soon as posible.**

 + Please do some steps to make your website work with github.io url
   + make sure relative url of ```css, js, images,...``` have no ```/``` at begining
   e.g ```href="css/bootstrap.min.css"```
   + change ```github-url``` property to website ```github.io``` Url, e.g ````xxx.github.io/repo-name/```
   + ```Rebuild``` on local (Refresh button) and ```Deploy``` again on github
 ![base config](https://github.com/easywebhub/easyapp/blob/master/documents/EasyWebBuilder/github-base-config.png?raw=true)