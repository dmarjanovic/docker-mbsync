Change Log
==========

Version 1.0.0 *(2020-05-25)*
----------------------------

 * New: Switch to S6 overlay for running cron in the container. This should generally make it more well-behaved.
 * New: `PUID` and `PGID` environment variables control what user and group the program runs (and thus writes files).


Version 0.2.0 *(2020-04-06)*
----------------------------

 * New: `HEALTHCHECK_ID` replaces `CHECK_URL`. This allows the container to ping the check both
   before and after the sync which will report its execution time.


Version 0.1.0 *(2020-04-06)*
----------------------------

Initial release
