Date: 2019-02-15
Categories: nyheter, server
Author: Karl Wettin
Description: New tile server
Summary: Upgraded to PostgreSQL 10.
Flags: front


# New tile server

We have deployed a new VM for the tile server, primarily to bump the PostgreSQL 9 to 10 
due to problems with keeping up with the incremental planet updates as our database grew larger and larger and left us stale with data from the summer of 2019 for a very long time.

We also optimized [the indices](https://github.com/karlwettin/carto-style-hydda/blob/master/create_indices.sql) for the Hydda-style
has which improved our tile rendering speed with a factor of 2 to 10 depending on zoom level.