---json
{
    "slug": "how-to-add-content-of-websites",
    "category": "tutorials",
    "tag": [],
    "layout": "Huong-Dan.html",
    "title": "How to add content of websites?",
    "description": "With EasyBuilder, you easily add, edit or delete content (pages, block, menu, footer,...) of websites. Developers could config the Editor to help Content users understand how to modify clearly.",
    "date": "2016-08-23 16:16:30",
    "featureImage": ""
}
---
### Brief Information
  + EasyWeb websites contains 2 parts:  Content and Layouts
  + EasyBuilder combines Content and Layouts and generate ```HTML``` files of websites.
  + There are 2 types of users: Developers who build websites and Administrators who manage websites

### Content of a website is
  + Common data of website is defined in ```Meta``` tab
	    + global information in ```global```
	    + menu in ```menu```
	    + footer in ```footer```
			+ Other information could be defined in other files
  + Data for a page of websites is defined in ```Content``` tab
      + ```index``` : default file contains data of index (home) page
      + data of each page must have 3 primary properties:  ```slug, layout, date``` which is automatically created when adding new Page
      
### What users could do with Content
  + Add, edit, delete pages of websites
  + Add Category, Tags of websites
  + Modify content of menu, footer, global 
  
### Content is files in Content and Meta tabs

    
###### 1. Content form: for Administrators
   + the simple form which help adding, modified or deleted content easily
   + restrict data which allows to modify

###### 2: RAW form: for Developers
   + actual data which is saved on files,
   + use RAW form to defined data structures which could be modified by Administrators