Replication package for Post-Incident Action Items: Crossroads
of Requirements Engineering and Software Evolution

We collected our data from Verica Open Incident Database (VOID): https://www.thevoid.community/


Files:

**void-data-subset.csv** The subset of 25 incident reports we selected from the VOID data set, following our inclusion criteria (described in the paper).

**coded-data/*.yaml** The action items, and associated coding, which we performed for each incident reports. For incident reports which had no action items, we labeled them as such. The format for each extracted action item is the following:

```
# Text description, providing context to the extracted action
2-1:  
  event: Responders turned off lower-priority features to reduce load
  Event: Load-shedding during response (feature based)
  
  action: Ask about feature switches early
  Action: Reinforce (enhance?)
  
  target: Design process
  Target: Process / Development methodology
  
  goal: Encourage feature flags and feature-based load-shedding 
  Goal: Add mitigation option / Feature based load-shedding

  memos:
  - Defense-In-Depth: (2-1, 2-2, 2-3) we’ve realized more clearly the value of [..] and identified several areas to reinforce the methodology
  - Prioritization: "realized more clearly the value of ..." 
  - This and below are from more-or-less SUCCESSFUL parts of the incident
```





> Matt Pope and Jonathan Sillito. 2024. Post-Incident Action Items: Crossroads
of Requirements Engineering and Software Evolution. In Proceedings of 46th
International Conference on Software Engineering (ICSE 2024). ACM, New
York, NY, USA, 7 page