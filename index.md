---
layout: index
---

Sarama is compatible with Go 1.1 and 1.2 (which means `go vet` on 1.2 may return some suggestions that we are ignoring for the sake of compatibility with 1.1).

A word of warning: the API is not 100% stable yet. It won't change much (in particular the low-level Broker and Request/Response objects could *probably* be considered frozen) but there may be the occasional parameter added or function renamed. As far as semantic versioning is concerned, we haven't quite hit 1.0.0 yet. It is absolutely stable enough to use, just expect that you might have to tweak things when you update to a newer version.

Other related links:

* https://kafka.apache.org
* https://cwiki.apache.org/confluence/display/KAFKA/A+Guide+To+The+Kafka+Protocol

## License

Copyright (c) 2013 Shopify. Released under the [MIT-LICENSE](http://opensource.org/licenses/MIT).