# Json-logger Sentry Extension

## 1.0.0 version - Release notes

About Sentry Connector:
* This plugin will publish events / exceptions (application logs) as JSON objects. Application logs published by this particular plug-ins follows the data format that is used to publish logs to Sentry. This plug-in can be instrumented in Mule-Soft platform to publish application logs in requested format. 
* Sentry is application log aggregator that collects logs published by multiple applications in an enterprise. Refer https://sentry.io/ 

## 1.1.0 version - Release notes

New features:
* Scoped loggers to capture "scope bound elapsed time". Great for performance tracking of specific components (e.g. outbound calls)
* Added "Parse content fields in json output" flag so that content fields can become part of final JSON output rather than a "stringified version" of the content

Improvements:
* Removed Guava and caching in general with a more efficient handling of timers (for elapsed time)
* Optimized generation of JSON output
* Code optimizations
* Minimized dependency footprint (down from ~23MB to ~13MB)
* Optimized parsing of TypedValue content fields

