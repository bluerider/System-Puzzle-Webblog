## Table of Contents
1. [Challenge](README.md#challenge)
2. [Running the code][READEME.md#Run)
3. [Struggles](README.md#struggles)

## Challenge
Fix a multi-container server tasked with high availability. Quantify availability by determining frequency of successful HTTP connections.
## Run
Run the code with `docker-compose up -d` and navigate to [site](localhost://8080) for the realtime frequency of successful HTTP connections.

## Struggles
1. Difficulty in resolving network due to systemd-networkd with Arch Linux was resolved by debugging the project in Ubuntu running on a QEMU-KVM. The issue seemed to be a long-standing bug associated with NetworkManager, dnsmasq, and systemd.

