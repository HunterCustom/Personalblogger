---
title: IT Portfolio
layout: page
icon: fas fa-network-wired
order: 0
permalink: /portfolio/
description: "Hunter Kovel's enterprise IT infrastructure experience, technical credentials, and personal projects in networking, servers, storage, Unraid, Docker, and virtualization."
---

I'm Hunter Kovel, an IT infrastructure and field service professional with experience at **IBM, Unisys, and Dell partner service organizations** supporting enterprise servers, storage, networking hardware, and client systems. My work combines independent on-site troubleshooting, hardware service, repair coordination, and customer-facing support. I'm building on that foundation with hands-on networking, systems, and infrastructure projects in my homelab.

[Connect on LinkedIn](https://www.linkedin.com/in/hunter-kovel-00836a224/) · [View my GitHub](https://github.com/HunterCustom) · [Email me](mailto:{{ site.social.email }})

## Professional experience

### IBM — Systems Services Representative

I provide on-site enterprise hardware service across customer environments in Connecticut and Massachusetts. My work includes diagnosing failures, replacing components, validating repairs, documenting service activity, and coordinating with remote support teams while independently managing field calls and travel.

The platforms and equipment I support include **Dell PowerEdge servers and client systems, NetApp storage, Lenovo ISG infrastructure, Cisco networking hardware, and Lexmark enterprise printing**. My client service experience spans banking, utilities, insurance, higher education, and other enterprise environments.

Alongside field work, I've completed IBM and vendor technical learning covering enterprise storage, server platforms, networking support, and service procedures. This training complements my hands-on hardware experience without being presented as production administration experience where that has not been established.

### Unisys — Field service and project coordination

I covered field service across Connecticut and Massachusetts and coordinated a repair project involving more than **3,500 PCs**, using ServiceNow to track the work. That experience strengthened my ability to organize service activity, follow issues through to resolution, and communicate progress.

### Dell client hardware service

Earlier in my career, I worked as a Dell technician repairing **laptops, desktops, and workstations**. That work gave me a strong foundation in client hardware diagnostics, component replacement, operating system and hardware troubleshooting, and customer-facing field service.

## Selected homelab projects

These are personal projects that I use to develop practical skills alongside my professional hardware service work.

### UniFi network segmentation

I configured dedicated VLANs, IPv4 subnets, and wireless networks for main, IoT, guest, and work devices using a **UDM Pro**, **US 24 PoE 250W switch**, and **U6+ access point**. I also configure port forwarding for hosted game services.

My documentation records the network and SSID mappings, the purpose of each segment, and the intended access policies. The next step is to add firewall rule details and connectivity test results.

**Skills demonstrated:** VLAN configuration, IPv4 subnetting, SSID mapping, managed networking, and NAT port forwarding.

### Dell PowerEdge R730 and Unraid

My primary homelab server runs **Unraid on a Dell PowerEdge R730** with dual **Xeon E5-2683 v4** processors, **384 GB DDR4 ECC memory**, dual **NVIDIA RTX A4000** GPUs, approximately **80 TB of usable storage**, and **3.9 TB of cache**. Most applications are containerized with Docker, including my Jellyfin media environment and supporting services.

I'm documenting the storage layout, container configuration, application dependencies, network access, and maintenance procedures so the environment is easier to understand and maintain.

**Skills demonstrated:** Enterprise server hardware, Unraid administration, Docker application hosting, storage management, GPU-backed workloads, and application troubleshooting.

[Read my earlier server specifications and plans]({% post_url 2024-01-01-Home-lab-plans %}) — a historical snapshot from 2024, rather than a current inventory.

### Lenovo M900 secondary server

A **Lenovo M900 Tiny** provides a second lab host with an **Intel Core i7-6700T**, **64 GB RAM**, and **1 TB mirrored storage**. I use it for additional Docker-hosted services and to separate selected workloads from the primary R730.

**Skills demonstrated:** Small-form-factor server deployment, mirrored storage, Docker hosting, service separation, and system maintenance.

### Virtual machines and remote access

I've deployed virtual machines and configured access from other computers around the house for personal testing and application use. Virtualization is an area I'm continuing to develop, with a focus on documenting guest resources, network connectivity, and access methods.

**Skills demonstrated:** VM deployment, resource allocation, and remote access.

## Certifications and accreditations

- **Cisco Certified Technician (CCT)**
- **NetApp Accredited Service Engineer 2 (ASE2)**
- **Lenovo ISG technical credential**
- **Lexmark enterprise printing technical credential**

## IBM and vendor technical training

My IBM learning history includes a much larger internal completion record; the items below are the training most relevant to the infrastructure roles I'm pursuing.

- **IBM FlashSystem Technical Essentials**
- **IBM Storage Insights Pro Technical Specialist**
- **NetApp AFF / ASA service training**
- **Lenovo ThinkSystem technical training**
- **SAN concepts and enterprise storage fundamentals**
- **Supermicro server service training**

These entries represent completed technical training and service learning. They are intentionally listed separately from certifications. My hands-on FlashSystem administration experience is currently limited, so I do not present the FlashSystem coursework as production storage-administration experience.

### Historical certifications and technical training

The following credentials represent training and accreditations I held during earlier Dell partner and field service work. They are listed for historical context and should not be interpreted as current or active credentials unless separately noted.

- **Dell Extended Partner Network** — renewed January 2024
- **Dell Technologies DSP Foundations v4** — renewed January 2024
- **Dell Security & Privacy Foundation 2024** — renewed January 2024
- **Dell Client Foundations v2** — renewed January 2024
- **Dell Client Advanced v3** — renewed January 2024
- **FAA Part 107 Remote Pilot Certificate** — issued November 2016

These credentials supported my work servicing Dell client systems and working in enterprise field-service environments. The Dell credentials are retained here as historical qualifications {% comment %} verify their current status before presenting them as active certifications. {% endcomment %}

## More project writing

My [HomeLab posts]({{ '/categories/homelab/' | relative_url }}) include server notes, self-hosting projects, and user documentation. One example is [moving my website to a self-hosted WordPress setup]({% post_url 2024-03-23-self-host-wordpress %}), which involved Docker application hosting and a domain migration.

## Get in touch

I'm relocating to **Burlington, North Carolina, in November 2026** and am interested in network support, systems and infrastructure support, data center infrastructure, enterprise field engineering, and systems administration opportunities that build on my experience.

For a copy of my résumé or to discuss an opportunity, [email me](mailto:{{ site.social.email }}) or [connect on LinkedIn](https://www.linkedin.com/in/hunter-kovel-00836a224/).

For more about the person behind the projects, visit my [About page]({{ '/about/' | relative_url }}).
