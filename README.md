# Joakim's Rancher Catalog

This catalog for Rancher has multiple items in various forms.

Such as:

## PostgreSQL Cluster

This adds the sameersben postgresql cluster with master and slave with:

* max_connections = 300
* shared_buffers = 2.5GB
* random_page_cost = 1 (ssd perf)

## Redis

Basic redis.

## Rancher Backup Special

Basically just rancher-backup with a fix for postgresql cluster dumping to /data/dump instead of /backup/dump for some reason.

## Install

Just add `https://github.com/jnylen/rancher-catalog.git` to your rancher catalog list.
