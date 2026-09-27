# HealthConnect-Appointment-Analysis-Week-8
HealthConnect healthcare appointment analysis using Power BI — KPI validation, no-show patterns, interactive dashboard, insights, and actionable recommendations.

<img width="512" height="288" alt="week 8 B" src="https://github.com/user-attachments/assets/60813eb8-2a85-447f-ad21-bc6d293ec2ac" />
<img width="513" height="292" alt="week 8" src="https://github.com/user-attachments/assets/155bcf8d-c6e6-49fa-9bbc-c26b876343c1" />


1. Project Overview

Week 8 marked the final stage of my HealthConnect appointment analytics project as part of the AnalystLab Africa Data Analytics Experience Lab.

The project focused on analyzing appointment attendance and no-show patterns and developing a Power BI dashboard that could be used to monitor important appointment-related indicators.

Rather than starting a new project, Week 8 focused on taking the work completed in the previous weeks and turning it into a more complete and validated analytics and decision-support package.

The main objective was to:

* Finalize the Power BI dashboard
* Validate the key KPIs
* Review and communicate the main analytical findings
* Convert findings into practical recommendations
* Improve dashboard usability and presentation
* Document analytical limitations
* Prepare the final project for presentation
* Document what I learned throughout the project

---

2. Business Problem

Missed healthcare appointments can affect scheduling, resource utilization, and the efficiency of healthcare services.

The HealthConnect project therefore focused on understanding:

* How many appointments were missed?
* What was the overall no-show rate?
* Did booking lead time differ across no-show patterns?
* Did previous no-show history relate to future attendance?
* Did travel distance show differences in attendance?
* Was there a difference between appointments with and without recorded reminders?
* How could the findings be communicated through an interactive dashboard?

---

3. Dataset

The HealthConnect dataset contained:

* 5,000 appointment records
* Multiple variables relating to appointments, attendance, reminders, distance, booking lead time, and previous appointment history.

The dataset was used consistently throughout the later stages of the AnalystLab Africa project.

---

4. Final Key Performance Indicators

The final validated KPIs included:

| KPI                | Result |
| ------------------ | -----: |
| Total Appointments |  5,000 |
| No-Shows           |  2,423 |
| No-Show Rate       | 48.46% |
| Attendance Rate    | 46.28% |
| Cancellation Rate  |  5.26% |
| Reminder Coverage  | 72.68% |

These KPIs provided the overall picture of appointment attendance before examining individual patterns.

---

5. Final Analytical Findings

Finding 1 — High level of missed appointments

The dataset recorded 2,423 no-shows out of 5,000 appointments, giving an overall no-show rate of 48.46%.

This shows that missed appointments represented a substantial proportion of the appointments in the dataset and therefore deserved attention in the analysis.

---

Finding 2 — Longer booking lead time showed higher no-show rates

Appointments booked further in advance showed higher observed no-show rates.

| Lead Time  | No-Show Rate |
| ---------- | -----------: |
| 0–7 days   |       27.81% |
| 8–14 days  |       33.55% |
| 15–30 days |       43.21% |
| 31–60 days |       60.49% |

The 31–60 day group recorded the highest observed no-show rate at 60.49%, compared with 27.81% among appointments booked 0–7 days in advance.

This suggests that booking lead time was an important pattern to monitor.

---

Finding 3 — Previous no-show history showed a clear pattern

Patients with a history of previous missed appointments had progressively higher observed no-show rates.

| Previous No-Shows | No-Show Rate |
| ----------------- | -----------: |
| 0                 |       43.51% |
| 1                 |       53.49% |
| 2                 |       59.36% |
| 3+                |       68.82% |

Patients with 3 or more previous no-shows had an observed no-show rate of 68.82%, compared with 43.51% among patients with no previous no-shows.

This makes previous appointment history a useful descriptive variable for identifying attendance patterns.

---

Finding 4 — Longer travel distance showed higher no-show rates

The analysis also showed differences in no-show rates across distance groups.

| Distance   | No-Show Rate |
| ---------- | -----------: |
| 0–5 km     |       46.45% |
| 5.1–10 km  |       46.51% |
| 10.1–20 km |       49.43% |
| 20+ km     |       57.76% |

Patients travelling 20 km or more had a 57.76% observed no-show rate, compared with 46.45% among those travelling 0–5 km.

Distance can therefore be considered when examining appointment attendance patterns.

---

Finding 5 — Reminder status showed a difference in observed no-show rates

The analysis compared appointments with and without a recorded reminder.

| Reminder Status   | No-Show Rate |
| ----------------- | -----------: |
| No reminder       |       51.39% |
| Reminder recorded |       47.36% |

Appointments with a recorded reminder had a lower observed no-show rate than appointments without a recorded reminder.

However, this is an observed association in the dataset and should not be interpreted as proof that reminders caused the difference.

---

Finding 6 — Reminder patterns were also observed across lead-time groups

When reminder status was examined alongside appointment lead time, appointments with reminders generally showed lower observed no-show rates across the lead-time groups.

This provided another useful perspective for the dashboard.

However, the analysis remains observational and does not establish a causal relationship between reminders and attendance.

---

6. Dashboard Development

The final Power BI dashboard was designed to provide an interactive view of the HealthConnect appointment data.

The dashboard incorporated:

KPI Cards

The KPI section communicated:

* Total appointments
* No-show rate
* Attendance rate
* Cancellation rate
* Reminder coverage

Charts and Visualizations

The dashboard was used to explore:

* Appointment attendance patterns
* No-show rates
* Booking lead time
* Previous no-show history
* Distance groups
* Reminder status

Slicers

Interactive slicers like Age Group, Gender, Reminder Sent, Appointment Type and Appointment Day were included to allow users to filter the dashboard and explore the data from different perspectives.

This helped make the dashboard more useful than a static collection of charts.

---

7. Dashboard Validation

One of the major lessons from Week 8 was the importance of validating an analytical dashboard before presenting it.

I reviewed:

* KPI values
* No-show calculations
* Attendance calculations
* Visual interactions
* Slicer functionality
* Chart labels
* Titles
* Readability
* Consistency between visuals
* Overall dashboard layout

The final dashboard was treated as a decision-support tool rather than simply a collection of visualizations.

---

8. Business Insights

The analysis provided several useful insights:

1. Almost half of the appointments in the dataset were recorded as no-shows.

2. Appointments booked further in advance showed higher observed no-show rates.

3. Patients with more previous no-shows also showed higher observed no-show rates.

4. Longer travel distances were associated with higher observed no-show rates.

5. Appointments with recorded reminders had a lower observed no-show rate than appointments without recorded reminders.

---

9. Business Recommendations

Based on the findings, the following recommendations were developed:

1. Monitor the overall no-show rate

The clinic can regularly monitor the no-show KPI to identify changes in appointment attendance over time.

2. Give additional attention to appointments booked far in advance

Appointments with longer booking lead times could receive additional follow-up or confirmation closer to the appointment date.

3. Monitor patients with previous missed appointments

Previous no-show history can be used as a descriptive indicator when reviewing appointment attendance patterns.

4. Consider travel distance during appointment planning

Distance can be included as an additional variable when examining attendance patterns and planning follow-up strategies.

5. Continue monitoring reminder coverage

Reminder coverage and attendance outcomes should continue to be monitored to understand how they relate to appointment attendance.

6. Continue using the Power BI dashboard for monitoring

The dashboard can be used as a decision-support tool for monitoring KPIs and identifying changes in appointment attendance patterns.

---

10. Analytical Limitations

An important part of Week 8 was learning that good analysis also requires clearly communicating its limitations.

The main limitations were:

* The dataset is a project dataset and may not represent all real-world healthcare settings.
* The analysis is observational.
* The findings show patterns and associations rather than proving causation.
* The dataset cannot explain every individual reason for a patient missing an appointment.
* Other factors that may affect attendance may not be included in the available data.
* Did not find a data science intern for the cross track collaboration.
* Additional data and further analysis would be required to investigate the underlying causes of no-shows.

---

12. What I Learned in Week 8

Week 8 helped me understand that data analytics involves much more than creating charts.

1. I learned how to validate analytical results

Before presenting a dashboard, I learned the importance of checking whether KPIs and visual outputs are consistent with the underlying analysis.

2. I improved my Power BI skills

I strengthened my ability to work with:

* KPI cards
* Charts
* Slicers
* Interactive filtering
* Dashboard layouts
* Visual formatting
* Analytical storytelling

3. I learned how to turn findings into recommendations

Instead of stopping at statements such as "the no-show rate is high," I learned how to connect findings to practical areas that an organization could monitor or investigate.

4. I learned the importance of avoiding unsupported conclusions

One of the most important lessons was understanding the difference between an observed relationship and causation.

For example, a lower no-show rate among appointments with recorded reminders does not automatically prove that the reminder caused the lower rate.

5. I learned how to communicate limitations

A good analyst should clearly explain what the data can and cannot show.

6. I learned how to build decision support dashboards

The purpose of a dashboard is not simply to make data look attractive. It should help users understand important information and support informed decisions.

7. I learned how to present analytical work

Week 8 also helped me improve my ability to explain:

* The business problem
* The data
* The findings
* The recommendations
* The limitations
* The value of the analysis

---

13. Skills Demonstrated

Through this project, I developed and demonstrated skills in:

Technical Skills

* Microsoft Power BI
* Data visualization
* KPI development
* Dashboard development
* Interactive slicers
* Data interpretation
* Analytical validation
* Descriptive analysis
* Dashboard testing and refinement

Analytical Skills

* Identifying patterns
* Comparing groups
* Interpreting KPIs
* Translating findings into insights
* Developing recommendations
* Recognizing analytical limitations
* Distinguishing association from causation

Communication Skills

* Data storytelling
* Executive-style summaries
* Dashboard presentation
* Business-focused recommendations
* Documentation
* Presenting analytical findings clearly

---

15. Final Project Outcome

The final outcome was an interactive Power BI dashboard and supporting analytical documentation for the HealthConnect appointment dataset.

The project provided a structured view of:

* Appointment volume
* Attendance
* No-shows
* Cancellations
* Reminder coverage
* Booking lead time
* Previous no-show history
* Travel distance

The project also demonstrated how analytical findings can be translated into practical areas for monitoring and further investigation.

---

16. Key Takeaway

My biggest takeaway from Week 8 is that:

Good data analysis is not only about finding numbers. It is about validating those numbers, understanding what they mean, communicating them clearly, and knowing the limits of what the data can tell you.

The HealthConnect project gave me practical experience in taking a dataset through the later stages of an analytics workflow and presenting the results in a way that can support decision-making.

---

19. Conclusion

Completing Week 8 marked an important stage in my Data Analytics learning journey with AnalystLab Africa.

The HealthConnect project allowed me to practice the full analytical process, from understanding a healthcare dataset and identifying patterns to building an interactive Power BI dashboard, validating results, communicating insights, and developing practical recommendations.

#AnalystLabAfrica #DataAnalytics #PowerBI #DataAnalyst #HealthcareAnalytics #DataVisualization #BusinessIntelligence
