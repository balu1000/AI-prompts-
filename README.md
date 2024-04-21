## AI-prompts-

## Опис

Маніфести YAML для кожного з наведених PROMPT.

## Таблиця маніфестів

| NAME                     | PROMPT              | DESCRIPTION                                 | EXAMPLE                                                    |
|--------------------------|---------------------|---------------------------------------------|------------------------------------------------------------|
| app.yaml                 | Basic app manifest  | Manifest defining a basic application.      | [Example](./yaml/app.yaml)                                |
| app-livenessProbe.yaml    | kubectl ai "app-livenessProbe;namespace: demo;gcr.io/k8s-k3s/demo:v1.0.0;ports;initialDelaySeconds;timeoutSeconds;failureThreshold;periodSeconds"      | Manifest demonstrating a liveness probe.   | [Example](./yaml/app-livenessProbe.yaml)                   |
| app-readinessProbe.yaml   | Readiness probe     | Manifest showing a readiness probe.         | [Example](./yaml/app-readinessProbe.yaml)                  |
| app-volumeMounts.yaml     | Volume mounts       | Manifest with volume mount configurations.  | [Example](./yaml/app-volumeMounts.yaml)                    |
| app-cronjob.yaml          | app-cronjob apiVersion: batch/v1beta1             | Manifest defining a cron job.               | [Example](./yaml/app-cronjob.yaml)                         |
| app-job.yaml              | Jkubectl ai "app-job-rsync batch/v1 gcePersistentDisk image google/cloud-sdk:275.0.0-alpine command -/bin/sh volumeMounts"                 | Manifest for running a one-off job.         | [Example](./yaml/app-job.yaml)                             |
| app-multicontainer.yaml   | Multi-container app | Manifest for a multi-container application. | [Example](./yaml/app-multicontainer.yaml)                  |
| app-resources.yaml        | Resource limits     | Manifest demonstrating resource limits.     | [Example](./yaml/app-resources.yaml)                       |
| app-secret-env.yaml       | Secret as env var   | Manifest using secrets as environment vars. | [Example](./yaml/app-secret-env.yaml)                      |

Будь ласка, перейдіть за посиланням вище, щоб переглянути кожен з маніфестів.