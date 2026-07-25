# 0x0. HTTPS SSL

## Description

This project focuses on configuring a domain zone so that subdomains point to the correct server IPs, and writing a Bash script to audit DNS records for those subdomains.

## Files

### `0-world_wide_web`

A Bash script that displays DNS record information (type and destination) for given subdomains of a domain.

**Usage:**
- `domain` (mandatory): the domain name to audit
- `subdomain` (optional): a specific subdomain to audit

If only `domain` is given, the script displays info for `www`, `lb-01`, `web-01`, and `web-02` in that order.

### Example
