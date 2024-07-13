---
title: Municipal Census Tool
publishDate: 2020-08-01 00:00:00
img: /assets/images/census.png
img_alt: Census map of Canada
description: |
  Online census gathering tool for municipalities
tags:
  - Development
  - Networking
  - Project Management
---

## Description

A multi-tenant, full stack Census tool for municipalities. The resident interface allowed secure completion of the census and responses to the census questions. An 'enumerator' interface was created to allow door-to-door canvasing by the census workers, using a tablet.  Extra care was needed for the enumerator interface as off-line use is highly likely. The administrative interface allowed authorized personnel to create a census, publish changes to production and monitor results as they arrived. The system handled 'bursty' data with a high volume of responses being submitted in a short period of time.  Multiple municipalities successfully ran their census, some with 1 million+ residents.  Due to the nature of the tool, we applied penetration testing and security audits to minimize potential attack vectors.

## Role

I was engaged by the municipality to review an existing tool that was based on much older technology and showing difficulties handling the modern requirements.  I proposed a new approach that would be more modern and easier to maintain, and should future-proof the staffing capabilities for many years.  Upon approval I drafted a project plan with a detailed design that incorporated the logic and capabilities of the older system.  Development began on this new system, with routine progress reporting.  Delivery dates were met, with full penetration testing and security analysis completed.

The system launched and successfully handled multiple Censuses in the province simultaneously.  In particular one municipality had more than 1 million residents resulting in very large network load in a short time frame.  The system handled this load with no more than 3% CPU utilization.  

I want to make a point that the administrative and support staff for this project were all amazing and made the process an enjoyable and memorable experience.
