---
title: 'Using the Tab element for Projects'
date: 2023-07-31 09:00:00 
category: ['Content','Posts & Pages']
tags: [pages,menu]
---

# Adding a menu item for a newly created page

In wordpress CMS, the menu is a seperate/stand-alone part of the site.  It does not automatically "add new pages".
For OHEJP site, the menu, as close as is possible, has been structured with the same hierarchy as the Pages structure and the Post's categories.  To naturally organise the data presented.

To add a new menu item, in the Admin area of the site, look for `Appearance` on the menu on the left and then select `Menu` under that.  This brings you to the Menu configuration page:

![Menu Editor](/assets/img/2023-07-31 11_15_11 - Menus-edit.jpg)

> As there is more than one menu on the OHEJP site, as a good practice, make sure you are editing the correct menu.  In this case it is the `New menu (Primary menu)`.
{: .prompt-info }

The menu items are all 'drag and drop' ready and this is how you will place a menu item in the right place and under the right parent. After adding a new menu item, it will always appear at the bottom of the menu and will need placing before saving.

To add a new menu item, select the 'content type' in the selector panel on the left:
![Choose Content Type](/assets/img/2023-07-31 11_23_15 - Menus-choosing-type.jpg)

Then simply select the item you wish to link to, from the menu and press `Add to Menu`.  This will create a new menu item at the very bottom of the menu of the menu list:
![Alt text](/assets/img/2023-07-31 11_27_31 - Menus-add-to-menu.jpg)

If you were to `Update` the menu now, the new menu item would appear on the top row and at the far right of the menu on the website.

To correctly position the menu item, you need to select and hold the menu item and drag it to where you can place it under it's intended parent and in a position 1 place to the right of the parent menu item:
![Placing a menu item](/assets/img/2023-07-31 11_39_15 - Menu-placing.jpg)

This creates a Parent/Child connection which displays the menu item as a sub-menu item of the Parent.

To further highlight this relationship, we need to add the right-pointing arrow icon for the menu item. Each menu item is configurable through the megmenu button which reveals itself when you hover over the menu item as shown in the image above.
Click this to display the menu item options and select `Icon` from the menu on the left.  Type 'arrow' into the search box on the far left and select the right-pointing arrow icon from the available arrow icons.

This config is auto-saved, so you can close the Menu Item config dialogue and all there is to do now, is to `Save Menu`.

> Each menu item is configurable with many options and will be covered in a seperate Help page
{: .prompt-info }
