.. Copyright 2017 FUJITSU LIMITED

.. _winmsiapplication-object:

winMsiApplication
=================

Provides information of a Windows Msi Application

Attributes
~~~~~~~~~~

The list of attributes for ``winMsiApplication`` are:

	* ``publisher`` (string): The publisher of the msi application
	* ``installLocation`` (string): the location the msi application is installed
	* ``estimatedSizeInKB`` (integer): the estimated size of the msi application
	* ``displayName`` (string): the name of the application
	* ``version`` (string): the version of the application
	* ``architecture``: the architecture of the application
	* ``parentUri`` (anyURI): the resource uri of the parent :ref:`windowsprofile-object` object
	* ``uri`` (anyURI): the resource uri of the application
	* ``created`` (dateTime): the created date of the object
	* ``dbId`` (long): the database id of the object
	* ``digest`` (string): the digest value (used for etag)
	* ``lastModified`` (dateTime): the last modified date of this object


