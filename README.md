# Monitoring node

## Description

This service manage node monitoring, using multiple components:
* CAdvisor
* Netdata
* Node exporter
* Process exporter
* Prometheus server


## Deployment and usage

* [Ansible role](https://gitlab.com/infopen/infrastructure/ansible-roles/ansible-role-monitoring-node)

Expected networks:
* `prometheus_servers`: for Prometehus federation


## Configuration files to manage

Some configuration files contains customer specific informations and must be managed by Ansible during deployments.

* Prometheus (scrapers & alerting rules)
