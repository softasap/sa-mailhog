sa-mailhog
==========

[![Build Status](https://travis-ci.org/softasap/sa-mailhog.svg?branch=master)](https://travis-ci.org/softasap/sa-mailhog)


Role to install mailhog on ubuntu based box. (with either upstart or systemd, as xenial)

Version is controlled by  mailhog_version parameter.


Example:

<pre>


     - {
         role: "sa-mailhog",
         mailhog_version: "1.6.0"
       }

</pre>
