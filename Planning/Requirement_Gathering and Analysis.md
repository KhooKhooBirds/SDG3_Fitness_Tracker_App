# Requirement Analysis Document

## Table of Contents
- [Requirement Gathering Overview](#requirement-gathering-overview)
- [Key Findings](#key-findings)
- [Features](#features)
- [Stakeholders](#stakeholders)
- [Functional Requirements](#functional-requirements-moscow-method)
- [Non-Functional Requirements](#non-functional-requirements)
- [User Stories](#user-stories)

---

## Requirement Gathering Overview

Our team utilized **Google Forms** and **Google Meets** as our primary tools for information gathering. These methods provided both quantitative and qualitative options, with the majority of users opting for quantitative responses. The survey was structured as pre-determined questions based on research of existing products on the market.

| Detail | Value |
|---|---|
| Sample Size | 38 respondents |
| Collection Period | 20th – 23rd February 2026 |
| Male | 63.2% |
| Female | 31.6% |
| Undisclosed | 5.3% |

The group was mostly **university students who are casual gym-goers**.

Additionally, **2 semi-structured interviews** were conducted via Google Meets. Respondents were made aware of the questions beforehand and provided consent. Both interviewees fell into the target demographic and provided responses that were later converted into user stories to inform the development of the application.

---

## Key Findings

Responses from the survey and interviews revealed the following key insights:

- 👥 Majority of stakeholders are **youth between the ages of 12–25 years**
- 😔 The largest factor impacting exercise consistency is **mood (57.9%)**, followed by stress (55.3%) and time constraints (47.4%)
- ⏱️ Nearly **70% of users** are willing to spend less than **3 minutes** inputting fitness data
- 📊 **Step Tracking (76.3%)** and **Progress Analytics (78.9%)** are expected MVP features; calorie calculators and diet recommendations are also preferred
- 🏆 **65.7%** of respondents agree or strongly agree that a reward system positively impacts their workout motivation
- 🎁 **Discount vouchers** and **digital milestones** are the primary reward motivators
- 👫 **71.1%** of users are open to **group reward challenges** over individual rewards

---

## Features

The key survey analysis highlighted the features most important to the target demographic, rated by demand. Demand informs the product backlog and development priority for producing a minimum viable product (MVP).

| Feature | Responses | % Approval | Demand |
|---|---|---|---|
| Progress Analytics | 30 / 38 | 78.9% | ⬆️ Very High |
| Step Tracking | 29 / 38 | 76.3% | ⬆️ Very High |
| Calorie Calculator | 24 / 38 | 63.2% | 🔼 High |
| Diet Recommendations | 23 / 38 | 60.5% | 🔼 High |
| Workout Video Tutorials | 19 / 38 | 50.0% | ➡️ Moderate |
| Water Intake Reminder | 18 / 38 | 47.4% | ➡️ Moderate |

---

## Stakeholders

User responses and interviews identified the following key stakeholders crucial to realizing the fitness tracker application:

1. **Active Users** — Young adults (81.6% of respondents aged under 25) identified as the intended target demographic.
2. **Reward System Partners** — Suppliers of discount vouchers and other physical rewards, identified through survey and interview responses.
3. **Design Team** — Responsible for developing app features based on the analysis provided.
4. **Team Leader** — Manages the overall project and tracks progress throughout the development cycle.

---

## Functional Requirements (MoSCoW Method)

The analysis of interviews and survey responses identified the following key functional requirements. The MoSCoW method is applied to classify priority based on recurring user stories.

| ID | Functional Requirement | Source | Priority |
|---|---|---|---|
| FR-01 | The app shall prioritize solo user experience | Survey (73.7%) | 🔴 Must Have |
| FR-02 | The app shall track steps taken | Survey (76.3%) | 🔴 Must Have |
| FR-03 | The app shall provide progress analytics | Survey (78.9%) and Interview 1 & 2 | 🔴 Must Have |
| FR-04 | The app should provide water intake reminders | Survey (47.4%) | 🟡 Should Have |
| FR-05 | The app shall have a reward system | Survey (65.8%) and Interview 1 & 2 | 🔴 Must Have |
| FR-06 | The app shall have discount vouchers or redeemable points | Survey (65.8%) | 🔴 Must Have |
| FR-07 | The app could have a leaderboard for select participants | Survey (26.3%) | 🟢 Could Have |
| FR-08 | The app could reward digital milestone badges | Survey (31.6%) | 🟢 Could Have |
| FR-09 | The app could have a group reward category | Survey (39.5% yes, 31.6% not sure) | 🟢 Could Have |

---

## Non-Functional Requirements

These attributes improve the overall quality of the application, derived from interviews and general market research of existing applications.

| ID | Non-Functional Requirement | Type | Source | Priority |
|---|---|---|---|---|
| NFR-01 | The app shall have a short logging process of less than 3 minutes | Performance | Interview 1 and Survey (68.4%) | 🔴 Must Have |
| NFR-02 | The app should be available at all times of the day to cater for different workout schedules | Reliability | Market Research | 🟡 Should Have |
| NFR-03 | The app should be visually pleasing | Usability | Interview 1 | 🟡 Should Have |
| NFR-04 | The app shall handle health data securely via encryption as per industry regulation | Security | Market Research | 🔴 Must Have |
| NFR-05 | The app should support real-time data syncing for multiple users for the leaderboard | Scalability | Survey and Market Research | 🟡 Should Have |

---

## User Stories

### 🎓 Interview Respondent 1 — Jack (University Student)

Jack is a university student who exercises irregularly due to academic responsibilities. His priorities centred on **progress tracking** and **reward systems** that would motivate consistent app use.

- As a busy student, daily fitness quests should be **short and flexible** to accommodate my school schedule.
- As a student, I want the ability to **adjust workout time and intensity** depending on my schedule.
- As a student, I wouldn't want to be **punished for rest days**, as that would be demotivational.
- As a student, I prefer **tangible rewards** over digital ones because they are more gratifying.
- As a student, I'd prefer **leaderboards to be optional** to avoid excessive competition.
- As an amateur gym-goer, I want to be **paired with similar users** to encourage participation and growth.
- As a user, I prefer **continuous metric tracking** readily available on the home page.
- As a user, I expect a **short and intuitive fitness logging process**.
- As a user, I would rather use **guest mode** to avoid a long login process.
- As a regular user, I want a **simple interface** for easy use.

---

### 💪 Interview Respondent 2 — Tammy

Tammy is more **intrinsically motivated** to exercise and is less affected by mood compared to the majority of other respondents.

- As an amateur gym-goer, **lucrative rewards like vouchers** would greatly motivate my continued app use.
- As an amateur gym-goer, I would prefer **personalised workouts** over general workout challenges.
- As a registered user, **physical rewards** like cash vouchers or medals would be preferred and provide more motivation than digital rewards.
- As a user, I would find a **leaderboard motivational** and it would encourage my engagement.
- As a student, **logging a workout should not be time-consuming**, as I would find a tedious process discouraging.
- As a university student, I would prefer tracking metrics for **food/diet or general progress**.
