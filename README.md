# openrewrite-example

This repository contains three examples of OpenRewrite recipes. They are available in  `example` folder, which contains a Kubernetes, Terraform and a Java project example.

For Kubernetes and Terraform examples, we use a recipe which applies best practices rules.

And for the Java project, we use a recipe which upgrade Spring Boot from version 2.7 to version 3.3.

## Quickstart

You'll need Docker installed.

```bash
docker-compose up [gradle-openrewrite-terraform|gradle-openrewrite-kubernetes|gradle-openrewrite-java]
```

Note: This comandline will use the Gradle Docker image to run OpenRewrite recipes.

Or you can run OpenRewrite directly with Gradle for a faster excecution:

```bash
gradle --build-file example/terraform/build.gradle rewriteRun
```

## Additional Links

These additional references should also help you:

* [OpenRewrite](https://docs.openrewrite.org/)
* [Gradle Installation](https://gradle.org/install/)
