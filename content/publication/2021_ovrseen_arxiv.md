---
title: "OVRseen: Auditing Network Traffic and Privacy Policies in Oculus VR"
authors:
- Rahmadi Trimananda
- Hieu Le
- Hao Cui
- Janice Tran Ho
- Anastasia Shuba
- Athina Markopoulou
date: "2021-06-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-06-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: Arxiv Preprint
publication_short: Arxiv Preprint

#abstract: Virtual reality (VR) is an emerging technology that enables new applications but also introduces privacy risks. In this paper, we focus on Oculus VR (OVR), the leading platform in the VR space and we provide the first comprehensive analysis of personal data exposed by OVR apps and the platform itself, from a combined networking and privacy policy perspective. We experimented with the Quest 2 headset and tested the most popular VR apps available on the official Oculus and the SideQuest app stores. We developed OVRseen, a methodology and system for collecting, analyzing, and comparing network traffic and privacy policies on OVR. On the networking side, we captured and decrypted network traffic of VR apps, which was previously not possible on OVR, and we extracted data flows, defined as <app, data type, destination>. Compared to the mobile and other app ecosystems, we found OVR to be more centralized and driven by tracking and analytics, rather than by third-party advertising. We show that the data types exposed by VR apps include personally identifiable information (PII), device information that can be used for fingerprinting, and VR-specific data types. By comparing the data flows found in the network traffic with statements made in the apps' privacy policies, we found that approximately 70% of OVR data flows were not properly disclosed. Furthermore, we extracted additional context from the privacy policies, and we observed that 69% of the data flows were used for purposes unrelated to the core functionality of apps.

# Summary. An optional shortened abstract.
#summary: Arxiv Preprint

featured: true

links:
url_pdf: https://arxiv.org/abs/2106.05407
---
