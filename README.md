# heroku-buildpack-load-test
Heroku buildpack contains load test tools such as JMeter, siege, httperf

## Usage
```
$ heroku buildpacks:set https://github.com/remore/heroku-buildpack-load-test.git

$ heroku run /bin/bash
Running `bash` attached to terminal... up, run.4131
~ $ jmeter --version
Copyright (c) 1998-2014 The Apache Software Foundation
Version 2.12 r1636949
```
