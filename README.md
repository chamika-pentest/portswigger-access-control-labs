# portswigger-access-control-labs
Professional write-ups of PortSwigger Web Security Academy labs focusing on access control vulnerabilities, including horizontal privilege escalation.

# PortSwigger Web Security Academy – Lab Write-Ups

## Overview
This repository contains professionally documented write-ups of selected
labs from the **PortSwigger Web Security Academy**, with a focus on identifying,
exploiting, and understanding common **web application security vulnerabilities**.

The primary goal of these write-ups is to demonstrate practical knowledge of
application security concepts, attack logic, security impact, and recommended
mitigations in a controlled and ethical lab environment.

---

## Covered Lab
### User ID Controlled by Request Parameter
- **Category:** Access Control / Horizontal Privilege Escalation
- **Difficulty:** Apprentice
- **Vulnerability Type:** Broken Access Control
- **Platform:** PortSwigger Web Security Academy

This lab demonstrates a horizontal privilege escalation vulnerability caused
by improper server-side authorization checks. By manipulating a user-controlled
request parameter, an authenticated user is able to access another user's
sensitive account information, including API keys.

---

## Key Learning Objectives
- Understand horizontal privilege escalation vulnerabilities
- Identify insecure direct object references (IDOR)
- Analyze the impact of broken access control mechanisms
- Practice safe testing using Burp Suite
- Learn effective mitigation strategies for access control flaws

---

## Tools and Technologies
- Burp Suite (Community / Professional)
- Modern Web Browser (Chrome / Firefox)
- PortSwigger Web Security Academy Lab Environment

---

## Repository Structure

