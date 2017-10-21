# ks

Kubernetes series

The objective of this series is to create a web application using kubernetes. We will evolve the application from a development enviroment to a production environment and add different pieces as we go.

## Why Kubernetes

To deploy, scale and manage containerized applications.

* [Why containers](https://kubernetes.io/docs/concepts/overview/what-is-kubernetes/#why-containers)
* [Why do I need Kubernetes and what can it do?](https://kubernetes.io/docs/concepts/overview/what-is-kubernetes/#why-do-i-need-kubernetes-and-what-can-it-do)
* [4 reasons you should use Kubernetes](https://www.infoworld.com/article/3173266/containers/4-reasons-you-should-use-kubernetes.html)

## Prerequisites

* [Yarn](https://yarnpkg.com/lang/en/docs/install/)
* [Docker](https://www.docker.com/get-docker)
* Kubernetes:
  * Follow this [tutorial](https://kubernetes.io/docs/tutorials/stateless-application/hello-minikube/) to set up kubernetes in your machine.

## Structure of this repo

* Each `ksx` folder (`ks1`, `ks2`, ...) contains a working example of the app we are building in this series.
* They are all incremental, so `ksn` is based on `ksn-1`, etc..
* instructions of each item of this series is in the `ksx.md` file.

## Getting started

1. clone ks repo
    ```bash
    git clone https://github.com/santiaago/ks.git
    ```

1. start following the series or go directly to the one you are interested in.

## Evolution of our app

1. [ks1: build a React app with kubernetes](./ks1/ks1.md)
1. [ks2: make minikube detect code changes](./ks2/ks2.md)
1. add a python web server that hosts an API
1. hook frontend and backend together
1. serve website (in a simple case as a webserver with frontend and api)
1. add a database
