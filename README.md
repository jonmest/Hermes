# Hermes
An advanced service health monitor

Most health checks performed on services today are primitive and only check that the service returns a 200 response when calling a healthcheck endpoint. The results of these health checks cannot really be extrapolated to make assumptions on the overall health of the service.
Further actions can be done to actively monitor the health of the service, for example by regularly verifying that the service is behaving as is intended - basically an ongoing test suite of a live production system.

Approaches:
- Given the request, expect this response
- Given the request, do replicas of a service provide a consistent response?
