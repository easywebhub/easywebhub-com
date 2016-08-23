---json
{
    "slug": "how-to-add-content-of-websites",
    "category": "tutorials",
    "tag": [],
    "layout": "Huong-Dan.html",
    "title": "How to add content of websites?",
    "description": "With EasyBuilder, you easily add, edit or delete content (pages, block, menu, footer,...) of websites. Developers could config the Editor to help Content users understand how to modify clearly.",
    "date": "2016-08-23 16:16:30",
    "featureImage": "img/ewb-content.png"
}
---
### Summary Information
  + EasyWeb websites contains 2 parts:  Content and Layouts
  + EasyBuilder combines Content and Layouts and generate ```HTML``` files of websites.
  + There are 2 types of users: Developers who build websites and Administrators who manage websites

### Content contains
  ##### 1. Common data in ```Meta``` tab
+ global information in ```global``` file
+ menu in the ```menu``` file
+ footer in ```footer``` file
+ Category data in  ```[Category]xxx``` files
+ Other information could be defined in other files
			
 ##### 2. Data of page ```Content``` tab
* default file ```index```  contains data of index (home) page
* data of each page must have 3 primary properties:  ```slug, layout, date``` which is automatically created when adding new Page
  
### Content has displayed in 
  
###### 1. Content form: for Administrators
   + the simple form which help adding, modified or deleted content easily
   + restrict data which allows to modify

###### 2: RAW form: for Developers
   + actual data which is saved on files,
   + use RAW form to defined data structures which could be modified by Administrators

##### 3. Layout tab: 
   + quick reference to the layout which applied the Content data
 
##### 4. Config tab
![](https://easywebhub.com/img/ewh-config.png)
   + config Content data which will showed for administrators
   + config type of data such as ```Text, Media, DateTime,...```
   + config the data could be modified by Administrator or not
   + hide data  in Content form
      
### What administrators could do with Content
  + Add, edit, delete pages of websites
  + Add Category, Tags of websites
  + Modify content of menu, footer, global 
  + Config the display Content form clearly