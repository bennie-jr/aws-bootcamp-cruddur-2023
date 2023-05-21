# Week 2 — Distributed Tracing

## Required Tasks

### Watch The Videos

I was able to watch the Week 2 live stream, Chirag's tutorial on spend considerations, Ashish's tutorial on observability security consideration and the other videos on picking the right cloud role, github codespaces and AWS Cognito security best practices.

### Configure custom logger to send to CloudWatch Logs

Configured a custom logger to send data to my AWS CloudWatch Logs

### Integrate Rollbar and capture and error

I was able to integrate Rollbar into the the cruddr app but there seems to be a problem with the Rollbar service so the data could not be sent or received.
 
### Instrument Honeycomb with OTEL
 
I was able to instrument Honeycomb into the cruddr app. I added custom instrumentation to Honeycomb to add more attributes eg. UserId etc. I also added a custom spans into the app so that data can be sent to Honeycomb. Data was successfully received on Honeycomb and I was able to visualize the data by running custom queries.

### Instrument AWS X-RAY and AWS X-RAY Subsegments

Instrumenting AWS X-RAY into the app was done successfully by implementing X-Ray recorder subsegments and X-RAY middleware. I was able to pinpoint where exactly in the app data was needed to captured with X-RAY capture and the data was successfully sent to AWS X-Ray traces on CLoudwatch.
