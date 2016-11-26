# Data Driven Post-Mortems
_Jason Yee, works at Datadog_

https://osem.seagl.org/conference/seagl2016/program/proposal/127
Slides at: bit.ly/seagl-postmortems
$0.5M/hour of downtime at PuppetLabs

# Metrics

## Work Metrics
* throughput
* success
* error
* performance

## Resource Metrics
* utilization
* saturation
* error
* availability

## Events
Things to correlate to Metrics
* code changes
* config changes
* scaling events

## Qualities of Good Metrics
1. must be understood
* sufficient granularity
* tagged and filterable - allows you to do query-based monitoring
* long lived - so you can see the cycles

## The Human Element

### What data to collect from a human?
* what they did
* what they thought
* why they thought/did it
* ask open ended questions
* include pictures

### When do you post-mortem?
* ASAP but imperative to do it within 2 days
* memory drops sharply within 20 minutes, levels off around 2 days
* susceptibility to false memory increases

### Data Skews
* stress
* sleep deprivation
* burnout
* blame/fear of punitive action

### Bias
* anchoring
* hindsight
* outcome
* availability (associate recent events with incident)
* bandwagon effect


## Postmortem Template
1. Summary
  * Impact
  * Severity
  * Components Affected
  * What Fixed It
2. How was the outage detected?
3. How did we respond?
* Why did it happen?
* How do we prevent in the future?
  * Links to ticket tracking
  * Now
  * Next
  * Later
  * Follow up notes
