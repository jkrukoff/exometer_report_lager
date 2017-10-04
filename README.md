# Exometer lager reporter

## Usage

This reporter is meant to be used with
[exometer_core](https://github.com/Feuerlabs/exometer_core).

### exometer\_report\_lager

Exometer reporter for lager backend.

This reporter emits messages to the lager logging backend,
at a reporting level chosen by the user (default: `notice`).

To change the reporting level, pass the option `{level, Level}`.

## Lineage

This is a direct copy of the original lager reporter from previous versions of
exometer\_core. When exometer\_core removed its dependency on lager, it also
removed the built in lager reporter. I've extracted that reporter to here in
order to continue using it.

Overall project structure stolen from the
[exometer_report_statsd](https://github.com/MyMedsAndMe/exometer_report_statsd)
package and used as an initial skeleton.
