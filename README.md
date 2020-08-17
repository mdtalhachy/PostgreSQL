# PostgreSQL

<img src="imageholder/postgresLogo.jpeg" width="500" height="250">

# Installing postgreSQL on Windows

In this guide, we're gonna install postgres on Windows and try running some helpful commands

# Table of Contents

* What is PostgreSQL
* Installing PostgreSQL on Windows
* Quick Run
* Common Issues with Windows Users 

# What is PostgreSQL

PostgreSQL is a powerful, open source object-relational database system that uses and extends the SQL language combined with many features that safely store and scale the most complicated data workloads. The origins of PostgreSQL date back to 1986 as part of the POSTGRES project at the University of California at Berkeley and has more than 30 years of activedevelopment on the core platform.

# Installing PostgreSQL on Windows

**_step 1_**: [Download](https://www.enterprisedb.com/downloads/postgres-postgresql-downloads) the latest version according to your system properties, `32 bit` or `64 bit`.

**_step 2_**: Install it like like any other software. 

Leave all the boxes checked when this appears

![](imageholder/components.PNG)  

When the prompt asks for a password, enter one you can easily remember (which will be needed later)

![](imageholder/password.PNG)

Keep pressing Next until you reach this prompt, uncheck the box and finish installation

![](imageholder/unchecklast.PNG)

# Quick Run

Now that postgres is installed in your system, go to the search bar at the bottom of the screen and type psql and drag the matching icon to desktop. Then do the same for pgadmin.

Now you're all set to run postgres. 

Double click on SQL shell you dragged earlier to your desktop. A cmd-like prompt will open. 

![](imageholder/shellstep1.PNG)

Keep pressing `Enter` until the prompt asks for a password.

![](imageholder/shellstep2.PNG)

Now enter the password you gave during installation. Once you've done that, you're all set to run Postgres commands. 

![](imageholder/shellstep3.PNG)

# Common Issues with Windows Users

If you try to import a file using file location on windows like this `\i D:\somefile.sql` you won't likely be able to do it. 
You can fix this issue with a slight change like this `\i 'D:\somefile.sql'` 
