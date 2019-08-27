#Final project for CS50w 2019.

 A Django APP which integrates with the Cisco Software Defined Network Controller (DNA Center).

The Cisco SDN Controller, also referred to as DNAC provides a REST API (Intent API) that exposes capabilities
 of the Cisco Platform. This Django app utilizes the Intent API to gather and store periodically health-
 statistics from DNAC.
 
Cisco DNAC can also send events and noticiations using webhooks. This Django app can receive these
events and store them to allow the user to search through these logged events.

More information regarding the DNAC capabilities can be found here:

https://developer.cisco.com/docs/dna-center/#!cisco-dna-center-platform-overview

=============================

python manage.py createsuperuser --username=admin --email=admin@example.com
The following credentials are set to manage the database.

Superuser	Pass
admin	cs50final