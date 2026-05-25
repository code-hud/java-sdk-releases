# java-sdk-releases
Release artifacts for the Hud Java code sensor.

Hud is a runtime layer that runs alongside application code in production to detect errors, performance regressions, and CPU spikes, and to capture forensic context (stack traces, parameters, code paths) about the events it observes.

This repository contains the published releases of the Java agent. The agent is attached to a JVM process via the standard `-javaagent` flag and collects runtime data from the target application without code changes. 

For more information, see [hud.io](https://www.hud.io/) or the [installation docs](https://docs.hud.io/docs/java-installation).
