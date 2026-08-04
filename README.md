
# LAN Attacks Analysis  
## Graduation Project Documentation  

**Project Team Leader:** [Nouran Salah Mohamed Hussien Sultan]

---

## 1. Project Overview
LAN Attacks Analysis is a project that focuses on understanding how internal network attacks are detected, categorized, and visualized. The project turns raw security event data into actionable insights that help decision-makers identify attack patterns, peak risk periods, and the most targeted network segments.

### Project objectives:
- attack events across the local network environment.  
- total Analyze attack trends by time, severity, protocol, segment, and source.  
- Identify high-risk and recurring attack patterns.  
- Support faster incident response through clear visual dashboards.  

### Project scope:
- Security-event analysis and dashboard reporting in Power BI.  
- Identification of key indicators such as total attacks, peak attack periods, and severity distribution.  
- Trend analysis across date, day, hour, attack type, and network segment.  
- Insight generation for operational and management decision-making.  

---

## 2. Project Planning & Management

### 2.1 Project Proposal
The project proposes a data-driven monitoring solution for LAN security events. Instead of reviewing raw logs manually, the dashboard summarizes the data in a visual and interactive way so that security trends become easier to understand and act upon.

---

### 2.2 Project Plan

| Phase | Main Activities | Output | Status |
|------|----------------|--------|--------|
| Data understanding | Review source fields and identify useful security indicators | Data model notes | Completed |
| Data preparation | Clean columns, standardize labels, and create time-based fields | Prepared dataset | Completed |
| Analysis design | Define KPIs, charts, and dashboard structure | Dashboard plan | in progress |
| Dashboard building | Build visuals and interactive filters in Power BI | Interactive report | Completed |
| Documentation | Write report, methodology, and submission documents | Project documentation | In progress |

---

### 2.3 Risk Assessment & Mitigation Plan

| Risk | Impact | Mitigation |
|------|--------|------------|
| Missing or incomplete data | medium | Validate fields early and document assumptions |
| Wrong dashboard interpretation | Medium | Add clear labels, legends, and notes |
| Late submission | High | Keep a milestone checklist and backup files |
| Version-control issues on GitHub | Medium | Use a clean folder structure and test uploads |

---

### 2.4 KPIs

| KPI | Meaning | Target/Use |
|-----|--------|------------|
| Total Attack | Number of recorded security incidents | Measure overall threat volume |
| Peak Attack Count | Highest number of attacks in a selected period | Identify the busiest risk window |
| Risk Score Trend | Combined severity indicator across events | Track threat intensity over time |
| Top Source / Segment | Most active origin of attacks | Prioritize monitoring and response |
| Attack Frequency by Hour | Distribution of events across the day | Find suspicious time patterns |

---

## 3. Literature Review
The literature around network security analytics shows that attack detection is more effective when logs are transformed into visual and time-based intelligence. Common best practices include event classification, severity ranking, trend monitoring, and segmentation of traffic by source, destination, protocol, and time window.

- Attack monitoring dashboards help teams move from reactive investigation to proactive detection.  
- Time-based analysis highlights peak risk windows that are often missed in static reports.  
- Severity-based ranking supports prioritization when incident volume is high.  
- Network-segment analysis helps isolate where malicious activity is concentrated.  

### Key attack categories considered in the project:
- Scanning and reconnaissance attempts.  
- Unauthorized access and brute-force behavior.  
- Denial-of-service and traffic flooding patterns.  
- Spoofing, suspicious protocol usage, and abnormal packet activity.  
- Repeated high-severity events requiring escalation.  

### Literature review conclusion:
The reviewed concepts support the need for a dashboard that combines trend analysis, severity scoring, and interactive filtering. This project applies those ideas in a practical Power BI report tailored to LAN attack monitoring.

---

## 4.1 Stakeholder Analysis

| Stakeholder | Needs | Expected Benefit |
|------------|------|-----------------|
| Project supervisor | Clear documentation and aligned scope | Easy review and grading |
| Security analyst / reviewer | Fast identification of risky patterns | Better incident awareness |
| Project team | Simple, organized analysis workflow | Efficient delivery |
| Decision-maker | Actionable dashboard insights | Faster decisions |

---

## 4.2 User Stories
- As a supervisor, I want to see the most important security indicators on one screen so that I can quickly understand project value.  
- As a reviewer, I want to filter attacks by time and severity so that I can inspect suspicious patterns.  
- As a team leader, I want to compare attack trends across days and hours so that I can identify peak risk windows.  

---

## 4.3 Use Cases

| Use Case | Actor | Description |
|----------|-------|------------|
| View dashboard overview | Reviewer | Open the report and inspect the main KPIs and charts |
| Filter by time period | Reviewer | Choose date, day, or hour to focus on a specific attack window |
| Inspect severity pattern | Security analyst | Analyze how low, medium, and high severity events are distributed |
| Find top attack source | Security analyst | Identify the most active source segment or IP pattern |

---

## 4.4 Functional Requirements
- The system shall display total attack counts and key KPIs.  
- The system shall allow filtering by date, hour, severity, attack type, and segment.  
- The system shall present trend charts for attack frequency over time.  
- The system shall highlight the most critical risk windows and attack sources.  
- The system shall support visual comparisons across network dimensions.  

---

## 4.5 Non-functional Requirements
- The report should be easy to read and navigate.  
- The dashboard should load quickly for standard dataset sizes.  
- The visual design should remain consistent across all pages.  
- The solution should be maintainable and easy to update with new data.  
- The analysis should be accurate, transparent, and reproducible.  

---

## 5. System Analysis & Design

The main problem is that raw security logs are difficult to interpret without structured analysis. The project solves this by converting attack records into a clear analytical dashboard that supports threat awareness, prioritization, and communication.

