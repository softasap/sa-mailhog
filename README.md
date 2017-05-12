sa-mailhog
==========

[![Build Status](https://travis-ci.org/softasap/sa-mailhog.svg?branch=master)](https://travis-ci.org/softasap/sa-mailhog)


Role to install mailhog on unix based box. (with either upstart or systemd)

Version is controlled by  mailhog_version parameter.


Example:

```YAML


     - {
         role: "sa-mailhog",
         mailhog_version: "1.6.0"
       }

```


Usage with ansible galaxy workflow
----------------------------------

If you installed the sa-mailhog role using the command

`
   ansible-galaxy install softasap.sa-mailhog
`

the role will be available in the folder library/softasap.sa-mailhog
Please adjust the path accordingly.

```YAML

     - {
         role: "softasap.sa-mailhog"
       }

```



Copyright and license
---------------------

Code licensed under the [BSD 3 clause] (https://opensource.org/licenses/BSD-3-Clause) or the [MIT License] (http://opensource.org/licenses/MIT).

Subscribe for roles updates at [FB] (https://www.facebook.com/SoftAsap/)

Join gitter discussion channel at [Gitter](https://gitter.im/softasap)

