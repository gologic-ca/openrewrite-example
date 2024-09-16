# openrewrite-example

This repository contains two examples of OpenRewrite recipes. They are available in  `example` folder, which contains a Kubernetes and a Terraform example.

For these two examples, we use a recipe which applies best practices rules.

## Quickstart

You'll need Docker installed.

```
$ docker-compose up [gradle-openrewrite-terraform|gradle-openrewrite-kubernetes]
```
Note: This comandline will use the Gradle Docker image to run OpenRewrite recipes.

Or you can run OpenRewrite directly with Gradle for a faster excecution:
```
$ gradle --build-file example/terraform/build.gradle rewriteRun
```
