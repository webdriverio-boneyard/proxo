proxo
=====

network analysis plugin for WebdriverIO

Approximate plan:
- `proxo` implements a wdio service/plugin. 
- It’d require Selenium to be running, possibly via the [wdio selenium service](https://github.com/webdriverio/wdio-selenium-standalone-service)
- It'd also require `browsermob-proxy` to be running, which could be automatically installed and run using https://github.com/rackerlabs/browsermob
- The user would configure the host and port that `browsermob-proxy` should run on
- `proxo` would provide webdriverio commands to start recording, stop recording and get a HAR dump
- Could provide utilities for working with the HAR, parsing it into a nice format, analysing performance, etc.
