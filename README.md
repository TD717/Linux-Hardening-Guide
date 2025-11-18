Linux Hardening Guide (System Hardening Protocol)

This repository contains a concise but complete Linux hardening guide based on a fully implemented Ubuntu 24.04 LTS security configuration. The document walks through every step taken to reduce the attack surface, strengthen authentication, secure services, and deploy a hardened web application inside a VMware environment.
What the Guide Covers
Minimal installation, package reduction, and system preparation
Strong password policies, account lockout, secure UMASK, and Google Authenticator 2FA
User/group separation, custom sudo privileges, and resource limits
UFW firewall configuration (HTTP, HTTPS, log forwarding)
Automatic security updates (unattended-upgrades)
AppArmor verification, profile enforcement, and boot-time activation
Secure Apache + MySQL + PHP + Drupal setup with HTTPS, HSTS, permissions, and module hardening
Centralized logging using rsyslog (TCP/514) and MongoDB in Docker
Prototype automated container updates with Watchtower
Purpose
This guide demonstrates a real, end-to-end hardening approach aligned with CIS Benchmarks and practical cybersecurity principles. It is ideal for students, system administrators, and security beginners looking for a structured example of a hardened Ubuntu system.
