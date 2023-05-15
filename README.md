# Oracle AI Application Helm Chart

## Overview

Oracle AI is an advanced artificial intelligence platform, capable of providing speech-to-text, text-to-speech, and text-to-image conversions. It is built to run on FreeBSD and can be deployed in a Kubernetes environment using this Helm chart.

## Prerequisites

- Kubernetes 1.18+
- Helm 3.0+

## Getting Started

To install the chart with the release name `my-release`:

```bash
helm repo add oracle-ai https://github.com/LeoricCryotek/oracle.git
helm install my-release oracle-ai/oracle-ai
