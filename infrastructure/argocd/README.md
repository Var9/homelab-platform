# Argo CD

## Purpose

Argo CD is the GitOps controller for Homelab Platform v2.

After the initial bootstrap, Argo CD manages:

- Itself
- Infrastructure components
- Applications

GitHub is the single source of truth.

## Bootstrap

The initial installation is performed manually using the official Helm chart.

After installation, Argo CD becomes self-managed.

## Configuration

Primary configuration:

- values.yaml

## Management

Permanent changes must be committed to Git.

Manual kubectl changes are not permitted except during disaster recovery or temporary debugging.
