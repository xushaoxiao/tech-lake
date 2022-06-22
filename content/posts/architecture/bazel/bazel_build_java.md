---
title: "How to build SpringBoot project with Bazel"
date: 2022-06-21T21:37:00+08:00
description: Build a java project with Bazel tool.
menu:
  sidebar:
    name: Bazel build SpringBoot
    identifier: bazel_build_springboot
    parent: architecture
    weight: 30
hero: boat.jpg
mermaid: true
---

# Build Tutorial: Build a SpringBoot project

This tutorial covers the basic of building SpringBoot applications with Bazel. You will set up your workspace and build a simple SpringBoot project that illustrates key Bazel concepts, such as targets and `BUILD` files.

Estimates completion time: 20 minutes.

## What you'll learn

In this tutorial you learn how to:

- Build a target
- Visualize the project's dependencies
- Split the project into multiple targets and packages
- Reference targets through labels
- Deploy a target

## Before you begin

### Install the JDK.

1. Install Java JDK(preferred version is 11, however versions between 8 and 18 are supported).
2. Set the JAVA_HOME environment variable to point to the JDK.

    ```shell
        export JAVA_HOME="$(dirname $(dirname $(realpath $(which javac))))"
    ```

### Get the sample project

Retrieve the sample project from Bazel's GitHub repository.

```shell
    git clone https://github.com/b-mono/bazel-examples.git
```

The sample project for this tutorial is in the `bazel-examples/springboot-sample` directory and is structured as follow:

```
springboot-sample
|-- BUILD
|-- README.md
|-- WORKSPACE
|-- maven_dependencies.bzl
|-- maven_install.json
|-- maven_repositories.bzl
```