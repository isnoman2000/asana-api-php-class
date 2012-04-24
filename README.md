Asana API PHP class
===================

A PHP class that acts as wrapper for Asana API.
Lets make things easy! :)

It is licensed under the Apache 2 license and is Copyright 2012 Ajimix


Working with the class
----------------------

First declare the asana class

    $asana = new Asana("YOUR_COOL_API_KEY");

Enjoy...

Creating a task...

    $asana->createTask(array(
       "workspace" => "176825", // Workspace ID
       "name" => "Hello World!", // Name of task
       "assignee" => "bigboss@bigcompany.com", // Assign task to...
       "followers" => array("3714136", "5900783") // We add some followers to the task... (this time by ID)
    ));

Commenting on a task...

    $asana->commentOnTask("MY_BEAUTIFUL_TASK_ID", "Please please! Don't assign me this task!")

etc.

Read comments on class for class magic and read [Asana API documentation](http://developer.asana.com/documentation/) if you want to be a master :D

Author
------

**Twitter:** [@ajimix](http://twitter.com/ajimix)

**GitHub:** [github.com/ajimix](https://github.com/ajimix)