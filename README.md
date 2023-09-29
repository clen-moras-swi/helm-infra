# helm-infra

Chart for deploying web applications.

## Steps to update the chart using GitHub Actions

1. Update version in Chart.yaml & cr.yaml (use the same version for both)

## Add the chart repository

run `helm repo add squadcasthub https://squadcasthub.github.io/helm-infra/`

## Install the chart

run `helm install squadcast-helm squadcasthub/squadcast-helm`
