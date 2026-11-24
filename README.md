# Kuroshio Office — Architecture Portfolio

**Live Portfolio:** https://neptune537.github.io/
**Hosted Office Console:** https://tr7n7t7.com/kuroshio-office

This repository hosts a static engineering portfolio page for **Josh Henry** describing **Kuroshio Office**, an independent side project focused on deterministic multi-agent systems design.

## Overview

Kuroshio Office organizes autonomous software agents as supervised, role-bound services inside an observable workspace:

- **Agent Creation:** Agents are instantiated from declarative role manifests with isolated private state, bounded message inboxes, and on-demand ephemeral subagents for parallel fan-out tasks.
- **Agent Management:** An asynchronous slice scheduler coordinates execution over a sequenced append-only event log, paired with closed-barrier task tracking, inline policy and secret-fencing gates, multi-agent quorum checks, and automated failover routing across budget reserves.
- **Agent Hosting:** Compute-heavy workloads run on a primary workstation while lightweight coordination and standby services operate on private edge hardware, backed by out-of-band health probes, single-writer failover fencing, checksummed encrypted backups, and a globally served static web console.

## Contents

- `index.html` & `portfolio.css` — Zero-script architectural overview and direct routing to the hosted Kuroshio Office console.
- `resume.html` — Engineering resume and systems background.
