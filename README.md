# Timetable system

This is a PHP application which implements a timetable system, with booking and clash-checking facilities.

It does not provide auto-scheduling.



Screenshot
----------

![Screenshot](screenshot.png)


Usage
-----

1. Clone the repository.
2. Download the library dependencies and ensure they are in your PHP include_path.
3. Download and install the famfamfam icon set in /images/icons/
4. Add the Apache directives in httpd.conf (and restart the webserver) as per the example given in .httpd.conf.extract.txt; the example assumes mod_macro but this can be easily removed.
5. Create a copy of the index.html.template file as index.html, and fill in the parameters.
6. Access the page in a browser at a URL which is served by the webserver.


Dependencies
------------

* [application.php application support library](https://download.geog.cam.ac.uk/projects/application/)
* [csv.php CSV manipulation library](https://download.geog.cam.ac.uk/projects/csv/)
* [frontControllerApplication.php front controller application implementation library](https://download.geog.cam.ac.uk/projects/frontcontrollerapplication/)
* hierarchy.php Hierarchy support library
* [ical.php iCal support library](https://download.geog.cam.ac.uk/projects/ical/)
* [jQuery.php jQuery abstraction library](https://download.geog.cam.ac.uk/projects/jquery/)
* [multisearch.php Multisearch library](https://download.geog.cam.ac.uk/projects/multisearch/)
* [pagination.php Pagination library](https://download.geog.cam.ac.uk/projects/pagination/)
* [pureContent.php general environment library](https://download.geog.cam.ac.uk/projects/purecontent/)
* [timedate.php Time/date utility library](https://download.geog.cam.ac.uk/projects/timedate/)
* [ultimateForm.php form library](https://download.geog.cam.ac.uk/projects/ultimateform/)
* [FamFamFam Silk Icons set](http://www.famfamfam.com/lab/icons/silk/)


Author
------

Martin Lucas-Smith, Department of Geography, University of Cambridge, 2012-2020.


License
-------

- Code license: GPL3
