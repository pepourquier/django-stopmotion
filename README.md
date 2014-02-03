django-stopmotion
=================

django-stopmotion is a django app to create stopmotion animation with Threesixty Slider

## Requirements ##

django-stopmotion is developed on a Ubuntu system running:
   * [Python](http://python.org) 2.7
   * [Django](http://djangoproject.com) 1.5
   * [Threesixty Slider](http://www.360slider.com) 1.0.7

## Basic use ##

    Install the django-stopmotion app in your apps directory
    Add it to your settings
    
    $ 'stopmotion'

    Syncronise the database
    
    $ python manage.py syncdb

    Run your server

    $ python manage.py runserver

## Credits and License ##

Pierre-Emmanuel Pourquier create this. 

This program is free software: you can redistribute it and/or modify it under
the terms of either the MIT License. See the file `COPYING.md` for details.

Threesixty Slider is a javascript plugin created by Gaurav Jassal. Released under the MIT and GPL Licenses.
