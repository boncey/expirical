expirical
=========

Generate an ical file of expiry dates from a list of domains
----

Expirical is a script that generates an ical file (to STDOUT) containing domain expiry dates for a given list of domains.  
So that I can get notified of when my domains expire.

It's intended to be run from cron on a regular schedule.

The resulting ical file can optionally be hosted on a webserver then subscribed to in OS X Calendar, Google Calendar etc so that it automatically picks up changes.

It's written in Ruby and uses [ruby-whois](https://github.com/weppos/whois) and [icalendar](https://github.com/icalendar/icalendar).


