---
title: "Grand Treatise of Modern Instrumentation and Orchestration"
speaker: Björn Rabenstein
video-id: HkEZ1LJ7kzQ
length: "0:00:00"
---
Go plays a major role in modern distributed systems. It is a great choice to implement microservices, as exemplified by the popular <a href="https://github.com/go-kit/kit">Go kit</a>. Even more convincing is the dominance of Go in the orchestration layer: <a href="http://kubernetes.io/" title="Kubernetes - Accelerate Your Delivery">Kubernetes</a>, <a href="https://coreos.com/etcd/">etcd</a>, and Weave's <a href="http://weaveworks.github.io/flux/">Flux</a> are just a few well-known examples.<br><br>Monitoring large-scale distributed systems including the underlying infrastructure poses an entirely new challenge. <a href="https://prometheus.io">Prometheus</a> was designed to meet that challenge. Unsurprisingly, it is written in Go, and it is not by coincidence that all examples given above feature some kind of Prometheus integration.<br><br>How can you, as a Go developer, integrate your own software? This talk will show you how to use the Prometheus client library for instrumenting your own code to expose Prometheus metrics and for writing small adapter applications to export metrics from 3rd-party systems. You will learn to identify and implement the metrics that are needed to enable meaningful service monitoring and alerting.