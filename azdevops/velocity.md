# Velocity metrics and usage guidance

```
Development teams around the world share one consistent goal: to release software. A release-based workflow is a set of patterns and policies that focuses on releasing software.
From a planning mindset, being release-centric means that issues are divided into distinct iterations that produce a new version. These iterations are often called sprints and are time-boxed in roughly equal periods to produce incremental changes.
```

* Lead time: measures the total time elapsed from the creation of work items to their completion
    * Lead Time is an example of a faster outcomes metric associated with an Azure DevOps project
      
* Cycle time: measures the time it takes for your team to complete work items once they begin actively working on them

* Burndown charts: focus on remaining work within a specific time period.
    * Burndown chart for a single iteration == Sprint burndown

* Cumulative flow diagrams ([CFD](https://learn.microsoft.com/en-us/azure/devops/report/dashboards/cumulative-flow?view=azure-devops))
   - monitor and count work items as they move to a different state.
   - CFD charts can be used to monitor the flow of work: in-context report and CFD widget.
   - most important CFD shows **botllenecks** in your process

![velocity](https://github.com/dejanu/az104/blob/main/src/velocitymetrics.PNG)

---

## Metrics

* Quality and security
    - Mean time to recover (MTTR)
    - SLA
    - Defect escape rate

* Performance and Efficiency metrics
    - Application performance index (Apdex)
    - Server to Admin ratio
    - Staff member to customer ratio

* Faster outcomes metrics
    - Lead time
    - Cycle time
    - Burndown charts
    - Cumulative flow diagrams (CFD)




