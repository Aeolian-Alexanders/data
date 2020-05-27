# SQLite Export of Aeolian aeolian_alexanders

This is an SQLite export of the major data tables for the Aeolian Alexanders application.

These do NOT contain the routing information necessary to construct spatial networks, as that would make the tables too large to upload. Also, pgRouting does not work with SQLite, so it is necessary to construct a postgis database to get that portion of the project to work.
