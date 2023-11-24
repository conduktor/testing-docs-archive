---
title: Building tests
description: Building tests with Conduktor Testing.
---

# Building Tests

Tests are used to validate that your applications that integrate Apache Kafka are working as expected.

Below outlines the basic terminology and entities that relate to test scenarios.

### Test Suite

- Suites represent a collection of test scenarios that are logically grouped together. We recommend organizing your test suites by feature, service, or a specific domain.
- See [Test Suites](/features/building-tests/test-suites) for more information.

### Test Scenario

- Scenarios represent a graph of tasks used to validate some functionality in your application, pipeline, or service.
- See [Test Scenarios](/features/building-tests/test-scenarios) for more information.

### Task

- Tasks are the building blocks that make up a test scenario. One task may represent producing data to Kafka, and another task may represent consuming from Kafka.
- See [Tasks](/features/building-tests/tasks) for more information.

### Test Check

- Boolean expressions used to validate a statement about the target under test. They execute against some data and return either a pass/fail result.
- See [Test Checks](/features/building-tests/test-checks) for more information.
