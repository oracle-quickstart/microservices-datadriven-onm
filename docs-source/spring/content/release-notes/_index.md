---
title: "Release Notes"
---

## Developer Preview 0.7.0, July 24, 2023

Notes:

* Continued incremental improvements to Oracle Database Adapter for Parse Server.

The following components were added:

| Component                    | Version   | Description         |
|------------------------------|---------------|---------------------|
| Coherence | 3.2.11 | Provides in-memory data grid. |

The following components were updated:

| Component                    | New Version   | Replaced Version    |
|------------------------------|---------------|---------------------|
| Oracle Backend for Spring Boot Visual Studio Code extension | 0.3.9 | 0.3.8 |
| HashiCorp Vault              |  1.14.0 | v1.11.3 |
| Oracle Database Operator for Kubernetes | 1.0 | 0.6.1 |
| Parse Server                 | 6.2.0  | 5.2.7 |
| Parse Dashboard              | 5.1.0 | 5.0.0 |
| Oracle Transaction Manager for Microservices | 22.3.2 | 22.3.1 |

There were no component deprecations or removals.

## Developer Preview 0.3.1, June 14, 2023

Notes:

* Improvements to Oracle Cloud Infrastructure (OCI) installation process.
* Continued incremental improvements to Oracle Database Adapter for Parse Server.

No components were added.

The following components were updated:

| Component                    | New Version   | Replaced Version    |
|------------------------------|---------------|---------------------|
| Oracle Backend for Spring Boot CLI | 0.3.1   | 0.3.0               |
| Oracle Backend for Spring Boot Visual Studio Code extension | 0.3.8 | 0.3.7 |

There were no component deprecations or removals.

## Developer Preview 0.3.0, April 17, 2023

Notes:

* Oracle Backend for Spring Boot now includes the option to install in a Multicloud (OCI/Azure) environment.
* The Oracle Database Operator for Kubernetes is bound to the existing Oracle Autonomous Database (ADB) created by infrastructure as code (IaC) in an all-OCI installation and provisions the ADB in the Multicloud installation.
* Improvements to On-Premises and desktop installation processes.

The following components were added:

| Component                    | New Version   | Description         |
|------------------------------|---------------|---------------------|
| Oracle Backend for Spring Boot Visual Studio Code extension | 0.3.7   |  Allows Visual Studio Code users to manage the platform, deployments and configuration.  |

The following components were updated:

| Component                    | New Version   | Replaced Version    |
|------------------------------|---------------|---------------------|
| Oracle Backend for Spring Boot CLI | 0.3.0   | 0.1.0               |

There were no component deprecations or removals.

## Developer Preview 0.2.3, March 8, 2023

Notes:

* Oracle Backend for Spring Boot now includes the option to also install Parse Platform in the same deployment.
* Oracle Backend for Spring Boot CLI 0.2.3 includes a number of bug fixes and adds support for custom listening ports for services.
* Apache APISIX is now pre-configured for both Eureka and Kubernetes service discovery.

The following components were added:

| Component                    | Version       | Description                                                                             |
|------------------------------|---------------|-----------------------------------------------------------------------------------------|
| Oracle Database Operator for Kubernetes | 0.6.1 | Helps reduce the time and complexity of deploying and managing Oracle databases.     |  
| Parse Server                 | 5.2.7        | Provides backend services for mobile and web applications.                               |
| Parse Dashboard              | 5.0.0        | Uses a web user interface for managing Parse Server.                                            |
| Oracle Database Adapter for Parse Server | 0.2.0    | Enables the Parse Server to store data in an Oracle database.                           |

The following components were updated:

| Component                    | New Version   | Replaced Version    |
|------------------------------|---------------|---------------------|
| Oracle Backend for Spring Boot CLI | 0.2.3   | 0.1.0               |
| cert-manager                 | 1.11.0        | 1.10.1              |
| NGINX Ingress Controller     | 1.6.4         | 1.5.1               |
| Jaeger Tracing               | 1.39.0        | 1.37.0              |
| Apache APISIX                       | 3.1.1         | 2.15.1              |
| Spring Boot Eureka service registry      | 2.0.1         | 2021.0.3            |

There were no deprecations or removals.

## Developer Preview 0.2.0, February 27, 2023

The following components were added:

| Component                    | Version       | Description                                                                             |
|------------------------------|---------------|-----------------------------------------------------------------------------------------|
| Oracle Transaction Manager for Microservices | 22.3.1 | Manages distributed transactions to ensure consistency across Microservices.   |
| Strimzi-Apache Kafka Operator       | 0.33.1        | Manages Apache Kafka clusters.                                                        |
| Apacha Kafka                 | 3.2.0 - 3.3.2 | Allows distributed event streaming.                                                            |

There were no deprecations or removals.

## Developer Preview 0.1.0, January 30, 2023

The following components were added:

| Component                    | Version      | Description                                                                              |
|------------------------------|--------------|------------------------------------------------------------------------------------------|
| HashiCorp Vault              | v1.11.3      | Provides a way to store and tightly control access to sensitive data.                    |
| Oracle Backend for Spring Boot CLI | 0.1.0  | Provides a command-line interface to manage application deployment and configuration.               |
| Netflix Conductor OSS        | 3.13.2       | Provides workflow orchestration for Microservices.                                       |
| On-premises installer        | 0.1.0        | Allows installation of a self-hosted stack.                                              |

There were no deprecations or removals.

## Developer Preview 0.0.1, December 20, 2022

This release includes the following components:

| Component                    | Version      | Description                                                                              |
|------------------------------|--------------|------------------------------------------------------------------------------------------|
| cert-manager                 | 1.10.1       | Automates the management of certificates.                                                |
| NGINX Ingress Controller     | 1.5.1        | Provides a traffic management solution for cloud native applications in Kubernetes.        |
| Prometheus                   | 2.40.2       | Provides event monitoring and alerting.                                                  |
| Prometheus operator          | 0.60.1       | Provides management for Prometheus monitoring tools.                                     |
| OpenTelemetry Collector      | 0.66.0       | Collects process and export telemetry data.                                              |
| Grafana                      | 9.2.5        | Examines, analyzes, and monitors metrics.                                                |
| Jaeger Tracing               | 1.37.0       | Provides a distributed tracing system for monitoring and troubleshooting distributed systems.       |
| Apache APISIX                | 2.15.1       | Provides full lifecycle API management.                                                  |
| Spring Cloud Admin server     | 2.7.5        | Manages and monitors Spring Boot applications.                                           |
| Spring Cloud Config server   | 2.7.5        | Provides server-side support for externalized configuration.                             |
| Spring Boot Eureka service registry      | 2021.0.3     | Provides service discovery capabilities.                                                 |
