check_mtr
=========

nagios plugin for monitoring mtr
requires ruby  should work with 1.8.x - 2.x

```
Usage: check_mtr [options]
    -h                               prints this menu
    -H, --host HOST                  which host to run mtr on
    -l, --latency_warn MS            latency to trigger warning in ms
    -L, --latency_crit MS            latency to trigger critical in ms
    -p, --packet_loss_warn PERCENT    packet lost percent to trigger warning
    -P, --packet_loss_crit PERCENT    packet loss percent to trigger critical
    -c, --count NUM                  number of times to ping host with
mtr
```
