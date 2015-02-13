# heroku-buildpack-load-test
Heroku buildpack contains load test tools such as JMeter, siege, httperf

## Usage
```bash
$ heroku config:add BUILDPACK_URL=https://github.com/ddollar/heroku-buildpack-multi.git

$ cat .buildpacks
https://github.com/remore/heroku-buildpack-load-test.git

$ heroku run bash
Running `bash` attached to terminal... up, run.4131
~ $ jmeter --version
Copyright (c) 1998-2014 The Apache Software Foundation
Version 2.12 r1636949
```
