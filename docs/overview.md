---
title: Overview
description: "RunPod is a cloud computing platform for AI, machine learning, and general compute, offering GPU and CPU resources, serverless computing, and a Command Line Interface for easy deployment and development."
sidebar_position: 1
---

**RunPod** is a cloud computing platform designed for AI, machine learning applications, and general computing needs.

Leverage our platform to execute your code using both GPU and CPU resources through our [Pods](/pods/overview) and [Serverless](/serverless/overview) computing options.

Start today by [signing up for an account](https://www.runpod.io/console/signup).

## What are Pods?

**Pods** allow you to run your code on GPU and CPU instances using containers.

### Secure Cloud vs Community Cloud

Pods are available in two deployment environments, each with different characteristics:

**Secure Cloud**
- Operates in professional T3/T4 data centers
- Provides high reliability with redundant power and networking
- Offers Network Volumes for persistent, shareable storage
- Recommended for mission-critical workloads and important data
- Ideal for production environments and sensitive applications

**Community Cloud**
- Connects vetted individual compute providers to consumers
- Offers competitive pricing through a peer-to-peer network
- Has variable reliability depending on individual providers
- No guarantee of persistent data storage
- Best for cost-sensitive workloads where data can be backed up elsewhere

For workloads where data persistence is critical, we strongly recommend using Secure Cloud with Network Volumes and implementing regular backups. Learn more about [data persistence in RunPod](/pods/storage/data-persistence).

## What is Serverless?

**Serverless** offers pay-per-second serverless computing with autoscaling capabilities for your production environment.

Define a Worker, create a REST API Endpoint for it, queue jobs, and enjoy autoscaling to meet demand.
This service, part of our Secure Cloud offering, ensures low cold-start times and robust security measures.

Get started with:

- [Building your own Worker image](/serverless/workers/overview)
- [Using any LLM with the vLLM worker](/serverless/workers/vllm/overview)

## Command Line Interface (CLI)

RunPod also provides a Command Line Interface (CLI) tool for quickly developing and deploying custom endpoints on the RunPod serverless platform.

For more information, see the following:

- [GitHub](https://github.com/runpod/runpodctl)
- [Reference documentation](/runpodctl/reference/runpodctl)

### Our mission

RunPod aims to make cloud computing accessible and affordable for everyone, without compromising on features, usability, or experience. We empower individuals and enterprises with cutting-edge technology to unlock the potential of AI and cloud computing.

For general inquiries, browse our documentation or reach out to us on [Discord](https://discord.gg/cUpRmau42V), our support chat, or by [email](mailto:support@runpod.io). More information is available on our [contact page](https://www.runpod.io/contact).

## Where to go next?

Learn more about RunPod by:

- [Creating an account](/get-started/manage-accounts)
- [Adding funds to your account](/get-started/billing-information)
- [Running your first tutorial](/tutorials/introduction/overview)
