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

    section DAGs
    GDA Platform Set-up         :    des11, after m0, 1w
    dev & Test Env              :    des12, after des11, 1w
    Document for KT             :    des13, after des12, 1w
    KT to Viz team              :    des14, after des13, 1w
    Practice for Viz team       :    des15, after des14, 1w
    Q&A                         :    des16, after des15, 1w

    section Views(dbt)
    Env Set-up                  :    des41, after des11, 1w
    KT from GDA                 :    des42, after des41, 1w
    dev & Test Env              :    des43, after des42,des13 1w
    Document for KT             :    des44, after des43, 1w
    KT to Viz team              :    des45, after des44, 1w
    Practice for Viz team       :    des46, after des45, 1w
    Q&A                         :    des47, after des46, 1w

    section Milestone
    Initial milestone           : milestone, m0, 2023-09-18,2min
    GDA Platform milestone      : milestone, m1, after des11, 2min
    Unload data milestone       : milestone, m2, after des12, 2min
    Document milestone          : milestone, m3, after des13, 2min
    KT milestone                : milestone, m5, after des14, 2min
```
<div class="x-scrollable">
<div style="width: 1800px;">
</div>
</div>
