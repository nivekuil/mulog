# μ/log -> OpenZipkin publisher
[![Clojars Project](https://img.shields.io/clojars/v/com.brunobonacci/mulog.svg)](https://clojars.org/com.brunobonacci/mulog)  [![cljdoc badge](https://cljdoc.org/badge/com.brunobonacci/mulog)](https://cljdoc.org/d/com.brunobonacci/mulog/CURRENT) ![CircleCi](https://img.shields.io/circleci/project/BrunoBonacci/mulog.svg) ![last-commit](https://img.shields.io/github/last-commit/BrunoBonacci/mulog.svg)


This project contains the `publisher` for [OpenZipkin](https://zipkin.io/)


## Usage

Please see [README](../README.md) on main page.

## Testing

``` shell
docker-compose rm -f && docker-compose up -d
```

Then open: http://localhost:9411/ for Zipkin UI

Here is an example of Zipkin traces:

![disruption traces](../examples/roads-disruptions/doc/images/disruption-trace.png)


## License

Copyright © 2019-2020 Bruno Bonacci - Distributed under the [Apache License v2.0](http://www.apache.org/licenses/LICENSE-2.0)
