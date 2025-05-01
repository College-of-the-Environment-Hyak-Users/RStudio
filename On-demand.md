# Running RStudio on Hyak using On-Demand feature

see also: https://hyak.uw.edu/docs/ood/start

---

**Pro at RStudio but would benefit from more resources? It is easier than ever to launch at RStudio Instance on Hyak.**


1. Go to https://ondemand.hyak.uw.edu/pun/sys/dashboard/


<img src="http://gannet.fish.washington.edu/seashell/snaps/Monosnap_Dashboard_-_Hyak_OnDemand_2025-05-01_11-59-05.png" width="300"/>

Click on Interactive Apps

<img src="http://gannet.fish.washington.edu/seashell/snaps/Monosnap_Dashboard_-_Hyak_OnDemand_2025-05-01_11-59-40.png" width="300"/>


2. Decide on what specific resources are available and needed.

You will be then be asked for information on resources you will ask for. 

<img src="http://gannet.fish.washington.edu/seashell/snaps/Monosnap_RStudio_-_Hyak_OnDemand_2025-05-01_12-04-18.png" width="300"/>

If you this is the first experience with Klone you it might be good to get familar with what resources are available to you.

For this you can login to Klone at command line from this webpage by clicking on `>_Klone Login` and entering your credentials.
From there you can run command `hyakalloc` to see what resources you have access to. 

<img src="http://gannet.fish.washington.edu/seashell/snaps/Monosnap_RStudio_-_Hyak_OnDemand_2025-05-01_12-07-21.png" width="600"/>

```
Last login: Thu May  1 10:23:40 2025 from 10.64.64.9
(base) [sr320@klone-login03 ~]$ hyakalloc
       Account resources available to user: sr320        
╭─────────┬──────────────┬──────┬────────┬──────┬───────╮
│ Account │    Partition │ CPUs │ Memory │ GPUs │       │
├─────────┼──────────────┼──────┼────────┼──────┼───────┤
│   coenv │      compute │   40 │   175G │    0 │ TOTAL │
│         │              │   25 │   138G │    0 │ USED  │
│         │              │   15 │    37G │    0 │ FREE  │
├─────────┼──────────────┼──────┼────────┼──────┼───────┤
│   coenv │       cpu-g2 │  736 │  5714G │    0 │ TOTAL │
│         │              │  592 │  3220G │    0 │ USED  │
│         │              │  144 │  2494G │    0 │ FREE  │
├─────────┼──────────────┼──────┼────────┼──────┼───────┤
│   srlab │ cpu-g2-mem2x │   32 │   490G │    0 │ TOTAL │
│         │              │    4 │    45G │    0 │ USED  │
│         │              │   28 │   445G │    0 │ FREE  │
╰─────────┴──────────────┴──────┴────────┴──────┴───────╯
              Checkpoint Resources               
╭─────────────────┬──────────────┬──────────────╮
│                 │         CPUs │         GPUs │
├─────────────────┼──────────────┼──────────────┤
│           Idle: │         4496 │          255 │
╰─────────────────┴──────────────┴──────────────╯
   Checkpoint is currently limited to 910 jobs
```
