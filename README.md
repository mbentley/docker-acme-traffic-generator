# mbentley/acme-traffic-generator

[Traffic generator](https://github.com/mbentley/acme_fitness_demo/blob/master/kubernetes-manifests/loadgen.yaml) for the [ACME Fitness Shop Demo App](https://github.com/mbentley/acme_fitness_demo)

I am not sure exactly how the traffic generator app was initially created as I can't find the Dockerfile but the verison posted to Docker Hub did not appear to be functional so I updated the load generator which appears to no longer error out on login.

```
docker build -t mbentley/acme-traffic-generator .
```

The deployment manifests can be found in the link above.
