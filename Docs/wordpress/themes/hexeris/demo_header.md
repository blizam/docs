---
title: Hexeris: Recreating the Demo - Header
description: Your Guide to Recreating Elements of the Hexeris Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/hexeris:Hexeris

---

Header Section
-----
![][demo]

Here is the widget breakdown for the Header section:

* Gantry Logo
* Gantry Divider
* Gantry Menu
* Gantry Divider
* RokAjaxSearch

The header section remains the same across the entire demo site. For this reason, it exists in the default **Widget Override** menu. It is also a fairly simple section to set up.

#### Gantry Logo
The first thing you will need to do is click and drag the **Gantry Logo** widget from the **Available Widgets** area of the Widgets menu to the appropriate section. Once this is done, the logo should appear in the upper-left area of the front page as it does in the demo. You can further customize this logo by following the instructions in our [FAQ][faq].

#### Gantry Divider
This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Gantry Menu
The Gantry Menu widget should be set to match your site's main menu as it serves as the primary menu widget for the entire site. You can customize this menu by navigating to **Administration -> Appearance -> Menus** and creating or modifying your selected menu there. 

Here is a breakdown of the widget options for this menu widget. Any options not present in this breakdown are left at default and should not be adjusted.

| Option            |   Setting |  
| :---------------- | --------: |  
| Menu              | Main Menu |  
| Menu Theme        |  Dropdown |  
| SplitMenu Style   |      None |  
| Limit Levels      |        No |  
| Start Level       |         0 |  
| End Level         |         0 |  
| Show All Children |       Yes |  
| Show Empty Menu   |        No |  
| Maximum Depth     |        10 |  
| Custom Chrome     |      Menu |  

#### RokAjaxSearch

The RokAjaxSearch widget allows users to search your site for interesting content. Here is a breakdown of the options you will want to change to match the demo.

* Enter `fp-rokajaxsearch` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

[demo]: assets/demo_1.jpeg
[faq]: faq.md