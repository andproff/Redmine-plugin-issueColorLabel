Issue Color Label - Redmine plugin
==============

Customize the Issues table display for Status, Tracker and Priority columns. 

Uses a JSON file as a database. Settings can be updated from the /admin page, accessing the "Issue Color Label" item. 
The plugin can be enabled / disabled from the same panel.
Administrators can update the settings, other users can only view.


Install
-----
Install by cloning repo `git clone git@github.com:andproff/Redmine-plugin-issueColorLabel.git issue_color_label` into the /plugins/ folder of your Redmine instance.
Then restart redmine server



Limitations / future development
-----
The settings can only be updated by an administrator. Uses plain CSS.<br/>
Working on improving the way options are set, migrating information to DB instead of using a .json file and working with custom fields and values.


Preview
-----
![](https://raw.githubusercontent.com/bogdananton/Redmine-plugin-issueColorLabel/master/preview.png)

Admin<br/>
![](https://raw.githubusercontent.com/bogdananton/Redmine-plugin-issueColorLabel/master/admin.png)
