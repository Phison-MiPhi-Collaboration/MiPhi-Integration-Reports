# MiPhi-Integration-Reports

This repository serves as a centralized location for maintaining **weekly update presentations, benchmarking results, integration logs, and demo videos** related to application integrations.

## Repository Structure

```text
MiPhi-Integration-Reports/
│
├── ppt/
│   └── Weekly Update PPTs
│
├── librechat/
│   └── Benchmarking results, logs, and demo videos
│
├── crewai/
│   └── Benchmarking results, logs, and demo videos
│
├── onyx/
│   └── Benchmarking results, logs, and demo videos
│
├── vane/
│   └── Benchmarking results, logs, and demo videos
│
├── dify/
│   └── Benchmarking results, logs, and demo videos
│
└── sim/
    └── Benchmarking results, logs, and demo videos
```

## Contents

### PPTs

The `ppt/` folder contains the **weekly update presentations** covering:

* Integration progress
* Implementation updates
* Benchmarking results
* Issues and debugging
* Demo updates
* Key findings

### Application Reports

Each application has a dedicated folder containing its integration-related reports and artifacts.

The planned applications are:

* **Onyx**
* **LibreChat**
* **CrewAI**
* **Vane**
* **Dify**
* **SIM**

Application folders may contain:

* Benchmarking results **with aiDAPTIV**
* Benchmarking results **without aiDAPTIV**
* Different context-length benchmark results
* Performance comparison data
* Configuration details
* Demo videos
* Supporting documentation

## Benchmarking

Benchmarking will be performed across different context lengths to evaluate the impact of **aiDAPTIV** integration.

Results will be maintained in two categories:

```text
Without aiDAPTIV
With aiDAPTIV
```

This allows performance and KV-cache offloading behavior to be compared under consistent test conditions.

## Purpose

The repository provides a single location to:

* Track weekly integration progress
* Maintain benchmarking history
* Store application-specific integration results
* Compare performance with and without aiDAPTIV
* Maintain demo videos and supporting logs
* Provide a version-controlled record of integration work
