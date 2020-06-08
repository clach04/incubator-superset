
Apache Superset
===============

See https://github.com/apache/incubator-superset

Notes for Actian Avalanche, Vector, ActianX, and Ingres.

This branch can be used with Actian database without special config when used with https://github.com/clach04/ingres_sa_dialect

Alternatively upstream/master can be used with a simple config change to `superset/config.py`, set:

    SQL_MAX_ROW = 0

This removes all LIMIT clauses from queries.
