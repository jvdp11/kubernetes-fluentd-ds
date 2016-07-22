daemonset deployment for kubernetes. This allows one instance of a fluentd pod on each node. You can set the following variables:

```
KUBERNETES_URL
KUBERNETES_VERIFY_SSL
ELASTICSEARCH_HOST
ELASTICSEARCH_PORT
```
More to be found here: [fabric8io/docker-fluentd-kubernetes](https://github.com/fabric8io/docker-fluentd-kubernetes)