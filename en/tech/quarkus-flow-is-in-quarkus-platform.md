# Quarkus Flow is Now Part of the Quarkus Platform

[Home](../../README.md) | [About this blog](../../about.md)

Starting with Quarkus 3.34, **Quarkus Flow** is officially part of the **Quarkus Platform**.

## What is Quarkus Flow?

[Quarkus Flow](https://docs.quarkiverse.io/quarkus-flow/dev/index.html) is a lightweight, native-friendly workflow engine for Quarkus, built on the CNCF Serverless Workflow Specification. It allows you to model both classic orchestrations and Agentic AI flows using a fluent Java DSL that maps directly to the specification’s core concepts (such as states, transitions, and event filters), all with first-class CDI and Quarkus ergonomics.

Source code: [github.com/quarkiverse/quarkus-flow](https://github.com/quarkiverse/quarkus-flow)

## What is the Quarkus Platform?

The [Quarkus Platform](https://quarkus.io/guides/platform) is a curated set of extensions that are tested together and guaranteed to work seamlessly. Platform extensions meet quality standards and receive coordinated releases, compatibility guarantees, and long-term support.

## What This Means for Users

No need to specify versions anymore - the Platform BOM handles it:

```xml
<dependency>
    <groupId>io.quarkiverse.flow</groupId>
    <artifactId>quarkus-flow</artifactId>
    <!-- Version managed by Platform -->
</dependency>
```

Quarkus Flow is also tested together with all other Platform extensions, so you can combine it with any Quarkus extension without version conflicts. When you upgrade Quarkus, Quarkus Flow automatically upgrades to a compatible version. Platform extensions receive regular security updates and bug fixes coordinated with Quarkus releases.

## What This Means for the Community

Platform inclusion increases visibility, leading to potential more adoption and feedback. A larger user base typically brings more contributors, documentation, and real-world examples. Closer ties with the core Quarkus team means better alignment with Quarkus roadmap and practices.

Quarkus Flow joining the Platform is a milestone that validates the project's maturity. For users, it means easier maintenance and better stability. For the community, it opens opportunities for growth and collaboration.

Want to contribute? Visit the [GitHub repository](https://github.com/quarkiverse/quarkus-flow).


---

© 2026 Tibor Zimányi. All rights reserved.