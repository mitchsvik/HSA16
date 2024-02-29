# HSA16
Mysql Slow Query Log 

This example provide simple configuration for ELK and GrayLog to track MySQL slow query log

### Slow query log

`long_query_time` can be set up in range 0 to 10 seconds with default value of 10.
If a query executing longer than defined value and `slow_query_log` set to `1` than this query will be logged.

Logs is shared with firebeat through `logs` folder `slow_query_log_file = /logs/mysql-slow.log`

### Logging

To check that logging workign - execute one of commenads from `probe.sql` in SQL console

