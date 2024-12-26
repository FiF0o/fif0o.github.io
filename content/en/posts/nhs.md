---
title: NHS - Test and trace
seo:
  slug: nhs
date: 2021-08-01
---

**NHS Digital – COVID-19 National Testing Platform:**

[[toc]]

## Summary

As Solution Architect for the NHS COVID-19 National Testing Program, I led the design and delivery of a digital platform that supported mass testing across the UK during the height of the pandemic.

The system enabled citizens to book appointments, register test kits, and receive results at national scale.

In parallel, we developed a Management Information (MI) integration layer to support public health reporting, dashboards, and decision-making.

<!-- {% image "/assets/img/rbs.jpg", "RBS 6 Nations iPhone application", "100vw", "RBS 6 Nations iPhone application", "square", "lazy", "auto", "async", "2400", "1600" %} -->

---

## Problem

The UK government faced an urgent need to implement a reliable, end-to-end digital infrastructure for COVID-19 testing—at scale, under extreme time constraints.

The platform had to process millions of weekly test registrations, support bookings at hundreds of test sites, ensure traceability of physical samples, and securely deliver test results to relevant stakeholders including individuals, local authorities, and GP records.

Legacy health systems were not built to handle this volume or complexity.

---

## Solution

I architected and oversaw the implementation of a secure, event-driven, cloud-native platform on AWS, capable of handling peak demand and real-time data integration across multiple stakeholders. Core achievements included:

- Digitisation of test site workflows, including booking, registration, check-in, and test kit tracking.

- Development of a Management Information (MI) platform, enabling near real-time reporting, dashboards, and high-level operational insight.

- End-to-end data flow design, ensuring timely and accurate transmission of results to local authorities, GP records, and individual users.

- Scalable system performance to support over 203 million tests, handling up to 100,000 tests per day within the first two months of launch.

- 60 code releases per month, with full CI/CD pipelines and incident recovery frameworks.

- 485 million page visits to the platform, with peaks of 3 million visits per day and no critical service interruptions.

## Outcome

The platform became the digital backbone of the UK’s national testing program, enabling massive scale with operational agility.

It empowered public health teams with real-time insight, supported citizen trust through timely results, and was instrumental in delivering over 203 million tests during the pandemic’s most critical period.

---