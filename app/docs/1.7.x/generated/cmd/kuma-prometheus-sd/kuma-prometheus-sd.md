---
title: kuma-prometheus-sd
---

[DEPRECATED] Prometheus service discovery adapter for native integration with Kuma

### Synopsis

[DEPRECATED] Prometheus service discovery adapter for native integration with Kuma.
It has been superseded by the native kuma_sd in Prometheus as of Prometheus 2.29.
See: https://prometheus.io/docs/prometheus/latest/configuration/configuration/#kuma_sd_config


### Options

```
  -h, --help                         help for kuma-prometheus-sd
      --log-level string             log level: one of off|info|debug (default "info")
      --log-max-age int              maximum number of days to retain old log files based on the timestamp encoded in their filename (default 30)
      --log-max-retained-files int   maximum number of the old log files to retain (default 1000)
      --log-max-size int             maximum size in megabytes of a log file before it gets rotated (default 100)
      --log-output-path string       path to the file that will be filled with logs. Example: if we set it to /tmp/kuma.log then after the file is rotated we will have /tmp/kuma-2021-06-07T09-15-18.265.log
```

### SEE ALSO

* [kuma-prometheus-sd run](/docs/{{ page.release }}/generated/cmd/kuma-prometheus-sd/kuma-prometheus-sd_run)	 - Launch Kuma Prometheus SD adapter
* [kuma-prometheus-sd version](/docs/{{ page.release }}/generated/cmd/kuma-prometheus-sd/kuma-prometheus-sd_version)	 - Print version

