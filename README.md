# Kamailio logstash parser

Straigh-forward Kamailio logging RegEx parser for logstash + logstash configuration example.

The pattern filter will return the following field list:
* kam_log_level: Kamailio's log level (ERROR, ALERT, INFO, NOTICE, etc...).
* kam_module: Kamailio's module generating the entry.
* kam_mod_func_location: Kamalio's module function location on core.
* kam_mod_function: Kamalio's module function generating the entry.
* kam_msg: Actual log message.
