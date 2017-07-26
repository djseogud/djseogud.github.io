---
layout: post
title:  "Some Scripts"
date:   2017-07-25 20:35:21
categories: Blog
---

In class we've been learning about scripts and databases and our fourth assignment integrated the two by challenging us to write simple yet effective scripts to handle user input and store raw data in MySQL. Basically, my collect-data script asks the user five survey questions. It then takes the users input and writes it to a temp csv file with a timestamp and a unique identifier. Lastly, it writes the data into a database which is created in the next script it calls while backing up and removing the temp files created. The second script creates the database and table with fields specified previously and writes the temp csv file into it. Finally, it dumps the current version of the database into an export file. Here is a link to my repository : [djseogud-4-data](https://github.com/djseogud/djseogud-4-data)
