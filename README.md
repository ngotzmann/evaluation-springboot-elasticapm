## Elastic APM Server integration

This simple spring boot service will test the integration to   
elastic apm and its behavior if the apm is not exists and something like this.

**Lost connection to apm**
* Log entries with the information that apm server is not reachable and it will retry to connect in X sec

**Starup behavior if apm server is not reachable**
* Service start up with the message that apm server is not available

**Will the data be saved during a downtime or will they got lost?**
* Data get lost

**Elastic APM vs Actuator with Micrometer**
* currently apm and micrometer does not work together there is a issue and in the beta version should it be supported  
  * https://github.com/micrometer-metrics/micrometer/issues/793
