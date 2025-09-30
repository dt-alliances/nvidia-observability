# Overview

This repo provides various guides to show how easy it is to setup and monitor the key tiers and components of the [NVIDIA enterprise stack](https://docs.nvidia.com/ai-enterprise), LLMs, and Generative AI applications with [Dynatrace](https://www.dynatrace.com).  

These guides are structured according the visual shown below.

<img alt="NVIDIA Enterprise Stack" src="images/nvidia-stack.png" width="50%">

## 1. AI Application Observability 

### 1.1 Dynatrace AI Observability

[Dynatrace AI Observability](https://www.dynatrace.com/hub/detail/ai-and-llm-observability/?filter=ai-ml-observability) brings End-to-End visibility to user interactions, prompt flows, and AI/LLM model performance of your Generative AI, agentic, and LLM services.

* [AI-observability](AI-observability.md) setup guide

### 1.2 NVIDIA NeMo Agent toolkit

The [NVIDIA NeMo Agent toolkit](https://github.com/robertjahn/NeMo-Agent-Toolkit) is a flexible, lightweight, and unifying library that allows you to easily connect existing enterprise agents to data sources and tools across any framework.  The NeMo Agent toolkit uses a flexible, plugin-based observability system that provides comprehensive support for configuring logging, tracing, and metrics for workflows. 

* [Observing a NeMo Agent toolkit workflow with Dynatrace and OpenTelemetry](https://github.com/NVIDIA/NeMo-Agent-Toolkit/blob/develop/docs/source/workflows/observe/index.md#available-tracing-exporters) setup guide

## 2. NVIDIA NIM, NeMo and technologies

Expanded observability coverage of exposed Prometheus metrics and OpenTelemetry telemetry from the various NVIDIA generative AI and lifecycle management tools and technologies. 

  * [NVIDIA NIM](NIM.md) setup guide

## 3. Kubernetes

Real-time auto-discovery and analysis of applications, NVIDIA platform components, and infrastructure.

* [Kubernetes](K8s.md) setup guide

## 4. GPU telemetry

Understand workload behavior or monitor GPUs in clusters

  * [DCGM-Exporter](DCGM-exporter.md) setup guide