---
layout: default
title: Test Page 0
nav_order: 2
parent: Synthesis
---

# This is a test page


## Adding Dropdown Menus to Projects 
Dropdown menus are a helpful way of organizing information. Here, on the Athena Website, we have several dropdown menus including "Courses and Tutorials" which will serve as the example for this tutorial. 

On Github, we have stored a "Courses and Tutorials" folder that contains the index mark down file (index.md) and the markdown files for each of the child pages. 

You will first need to add the following has_children attribute to your parent page's index file. For example, on this website, "Courses and Tutorials" is the parent page, and it extends the children "Core Readings", "Github", etc. 

![has_children](/images/has_children.png){:width="350px"}

Now that we've given "Courses and Tutorials" the has_children attribute and set it to true, a carrot (^) is displayed beside it. However, when you click on the carrot, there's nothing there. We still need to add the parent attributes to the children. Open the markdown file you wish to be contained within the dropdown menu, and add the parent attribute. Check the title attribute of the parent page to make sure you are attaching the correct page. 

![parent](/images/parent.png){:width="350px"}

You can also create dropdown menus within dropdown menus by adding a grand_parent attribute to the grand child, and adding a has_children attribute to the the child. 
