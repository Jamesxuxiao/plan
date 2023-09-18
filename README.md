# plan




```mermaid
gantt
    dateFormat  YYYY-MM-DD
    title       Data Viz Platform Optimization Plan
    axisFormat %e%b
    todayMarker on
    %%excludes    weekends
    tickInterval 2week
    %% (`excludes` accepts specific dates in YYYY-MM-DD format, days of the week ("sunday") or "weekends", but not the word "weekdays".)


    section A ridiculously <br> long section <br> name

    section DB objects(flyway)
    Env Set-up                  :    des11, after m0, 1w
    KT from GDA                 :    des12, after des11, 1w
    dev & Test Env              :    des13, after des12, 1w
    Document for KT             :    des14, after des13, 1w
    KT to Viz team              :    des15, after des14, 1w
    Practice for Viz team       :    des16, after des15, 4w
    Q&A                         :    des17, after des16, 1w
    
    section S3 bucket(Terraform)
    Env Set-up                  :    done,des31, after des17, 1w
    KT from GDA                 :    done,des32, after des31, 1w
    dev & Test Env              :    done,des33, after des32, 1w
    Document for KT             :    done,des34, after des33, 1w
    KT to Viz team              :    done,des35, after des34, 1w
    Practice for Viz team       :    done,des36, after des35, 4w
    Q&A                         :    done,des37, after des36, 1w

    section DAGs(Airflow)
    Env Set-up                  :    des21, after des37, 1w
    KT from GDA                 :    des22, after des21, 1w
    dev & Test Env              :    des23, after des22, 1w
    Document for KT             :    des24, after des23, 1w
    KT to Viz team              :    des25, after des24, 1w
    Practice for Viz team       :    des26, after des25, 4w
    Q&A                         :    des27, after des26, 1w

    section Views(dbt)
    Env Set-up                  :    des41, after des27, 1w
    KT from GDA                 :    des42, after des41, 1w
    dev & Test Env              :    des43, after des42, 1w
    Document for KT             :    des44, after des43, 1w
    KT to Viz team              :    des45, after des44, 1w
    Practice for Viz team       :    des46, after des45, 4w
    Q&A                         :    des47, after des46, 1w

    section Milestone
    Initial milestone : milestone, m0, 2023-03-27,2min
    Flyway milestone : milestone, m1, after des12, 2min
    Airflow milestone : milestone, m2, after des22, 2min
    S3 milestone : milestone, m3, after des32, 2min
    dbt milestone : milestone, m4, after des42, 2min
    Final milestone : milestone, m5, after des47, 2min
```
<div class="x-scrollable">
<div style="width: 1800px;">
</div>
</div>
