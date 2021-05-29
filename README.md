# Json-logger Sentry Extension

## 1.0.0 version - Release notes

About Sentry Connector:
* This plugin will publish events / exceptions (application logs) as JSON objects. Application logs published by this particular plug-ins follows the data format that is used to publish logs to Sentry. This plug-in can be instrumented in Mule-Soft platform to publish application logs in requested format. 
* Sentry is application log aggregator that collects logs published by multiple applications in an enterprise. Refer https://sentry.io/ 

## Operations Supported
Log Event:
* This pallet will publish log event as JSON object , based on input details provided

Log Scope:
* This pallet will publish log and provide details like time consumed in milliseconds for all the activities that is getting covered under particular scope. It will publish two logs one at the starting activity of Logger Scope and second log after completion of last activity in Logger Scope. It is majorly used to identify end-to-end time that got elapsed in any scope

