# PostGIS Cheatsheet

```sql
CREATE EXTENSION postgis;
SELECT ST_Distance(a.geom::geography, b.geom::geography) FROM ...;
SELECT ST_DWithin(geom::geography, other::geography, 5000);
CREATE INDEX ON t USING GIST (geom);
```
