# HealthConnect Week 6 — Advanced Analytics & Decision Support

## Overview

This repository contains the Week 6 Data Analytics deliverables for the HealthConnect project.

The analysis builds on the earlier no-show analysis by examining factors associated with appointment non-attendance and translating the observed patterns into business insights and recommended actions.

## Objectives

The Week 6 analysis focused on:

- Identifying factors associated with appointment non-attendance.
- Deepening the analysis of no-show behaviour.
- Developing decision-support insights from the available appointment data.
- Identifying candidate factors for future predictive modelling and testing.
- Presenting findings through a business-focused Power BI dashboard.

## Key Analysis

Four advanced analyses were developed:

1. **Appointment Type & No-Show Risk**
   - Compares observed no-show rates across appointment types.

2. **Previous No-Shows & Future Attendance**
   - Examines the relationship between previous no-show history and subsequent attendance behaviour.

3. **Longer Booking Lead Times Increase Risk**
   - Examines how no-show rates vary according to the number of days between booking and appointment.

4. **Reminder Channel & No-Show Rate**
   - Compares observed no-show rates across reminder channels.

## Key Takeaway

**Longer booking lead times and previous no-shows are the strongest observed indicators of non-attendance.**

The overall observed no-show rate in the analysed dataset was **48.46%**, representing **2,423 no-shows out of 5,000 appointments**.

These findings represent observed associations in the available data and should not be interpreted as proof of causation.

## Business Implications

The analysis suggests several areas for operational testing:

- Review appointments with longer booking lead times.
- Consider targeted confirmation or rescheduling processes for patients with previous no-shows.
- Investigate reminder-channel effectiveness further.
- Use the identified factors as candidate inputs for future predictive modelling.
- Validate proposed interventions before wider implementation.

## Data Limitations

The analysis has several limitations:

- Some high-risk groups contain relatively small numbers of appointments.
- The analysis identifies associations rather than causal relationships.
- Reminder-channel differences may be influenced by other patient or appointment characteristics.
- Further statistical validation and controlled testing are required before operational interventions are implemented at scale.

## Week 7 Testing Requirements

The following areas have been identified for further testing:

- Validate whether booking lead time remains a significant predictor of no-show behaviour.
- Test whether previous no-show history improves predictive performance.
- Evaluate reminder-channel effectiveness using appropriate statistical or experimental methods.
- Investigate potential confounding factors.
- Compare the Data Analytics findings with future Data Science model results when available.
- Validate proposed interventions before wider implementation.

## Deliverables

This repository contains:

- **Advanced Analytics & Decision Support Report**
- **HealthConnect Week 6 Power BI Dashboard (.pbix)**
- **Week 6 Project Summary**
- **Dashboard analysis evidence (.png)**

Cross-track collaboration evidence is maintained separately as supporting submission evidence.

## Cross-Track Collaboration

The Data Analytics track attempted to establish cross-track collaboration through the HealthConnect collaboration channel. No completed analytical/model output was received before the submission point.

The limitation is documented transparently, and the completed Data Analytics work provides an integration-ready hand-off for future modelling and validation.

## Tools

- Microsoft Power BI
- Power Query
- Excel / structured appointment data
- Data visualisation and analytical techniques

## Project

**HealthConnect — Week 6 Data Analytics Track**

Prepared as part of the AnalystLab Africa Data Analytics programme.
