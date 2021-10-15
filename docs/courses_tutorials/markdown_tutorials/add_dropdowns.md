---
layout: default
title: Adding Dropdown Menus
nav_order: 2
parent: Markdown Tutorials
grand_parent: Courses and Tutorials
---

## Adding Dropdown Menus to Projects 
Dropdown menus are a helpful way of organizing information. Here, on the Athena Website, we have several dropdown menus including "Courses and Tutorials" which will serve as the example for this tutorial. 

On Github, we have stored a "Courses and Tutorials" folder that contains the index mark down file (index.md) and the markdown files for each of the child pages. 

You will first need to add the following has_children attribute to your parent page's index file. For example, on this website, "Courses and Tutorials" is the parent page, and it extends the children "Core Readings", "Github", etc., but don't worry about the children quite yet.

![has_children](/images/add_dropdowns/has_children.png){:width="350px"}

Now that we've given the Courses and Tutorials index the has_children attribute and set it to true, a downwards pointing arrow is displayed beside it. However, when you click on the carrot, there's nothing there. 

![courses_and_materials](/images/add_dropdowns/courses.png){:width="200px"}

We still need to add the parent attributes to the children. Open a markdown file you wish to be contained within the dropdown menu, and add the parent attribute. Check the title attribute of the parent page (in this case, the Courses and Tutorials index.md file) to make sure you are attaching the correct page. 

![parent](/images/add_dropdowns/parent.png){:width="350px"}

You can also create dropdown menus within dropdown menus by adding a grand_parent attribute to the grand child, and adding a has_children attribute to the child. 

Here, I've added the grand_parent attribute to this page we're on (Adding Dropdown Menus).
![grand_parent](/images/add_dropdowns/grand_parent.png){:width="350px"}

Then I added the has_children attribute to the parent file, which for this example is the Markdown Tutorials file.

![child_has_children](/images/add_dropdowns/child_has_children.png){:width="350px"}

