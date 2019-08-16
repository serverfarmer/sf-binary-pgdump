sf-binary-pgdump is a dependency extension, providing Postgres pg_dump
command line tool (and required shared library).

It also provides a simple pg_dump wrapper script, which automatically
detects current OS version and architecture, and executes the proper
pg_dump binary, so user can just focus on pg_dump related logic.
