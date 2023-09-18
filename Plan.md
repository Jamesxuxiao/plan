# plan




```mermaid
gantt
    dateFormat  YYYY-MM-DD
    title       Data Viz Platform Optimization Plan
    axisFormat %e%b
    todayMarker on
    %%excludes    weekends
    tickInterval 1week
    %% (`excludes` accepts specific dates in YYYY-MM-DD format, days of the week ("sunday") or "weekends", but not the word "weekdays".)


    section A ridiculously <br> long section <br> name

    section DB objects(flyway)
    GDA Platform Set-up         :    des11, after m0, 1w
    dev & Test Env              :    des12, after des11, 1w
    Document for KT             :    des13, after des12, 1w
    KT to Viz team              :    des14, after des13, 1w
    Practice for Viz team       :    des15, after des14, 1w
    Q&A                         :    des16, after des15, 4w

    section Milestone
    GDA Platform milestone      : milestone, m0, 2023-09-25,2min
    Unload data milestone       : milestone, m1, after des12, 2min
    Document milestone          : milestone, m2, after des13, 2min
    KT milestone                : milestone, m3, after des14, 2min
    Final milestone             : milestone, m5, after des16, 2min
```
<div class="x-scrollable">
<div style="width: 1800px;">
</div>
</div>
