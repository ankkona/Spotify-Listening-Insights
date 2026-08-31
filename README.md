# 🎧 Spotify Listening Insights Analysis

## Objective

This project analyzes Spotify listening behaviour to identify patterns in listener engagement, skip behaviour, device usage, listening trends, and artist preferences, using data cleaning, analysis, and interactive visualisation.

## Tech Stack

* **Google Sheets** – Data preparation and initial analysis
* **Gemini AI** – Assisted data cleaning and analysis within Google Sheets
* **Power BI** – Data modelling, DAX measures, and interactive dashboard development

## 🔄 Project Workflow

```mermaid
flowchart TD
    A[Maven Analytics Dataset]
    B[Google Sheets]
    C[Gemini AI: Cleaning & Analysis]
    D[Prepared Dataset]
    E[Power BI]
    F[DAX Measures]
    G[Interactive Visualizations]
    H[Spotify Insights Dashboard]

    A --> B --> C --> D --> E --> F --> G --> H


## Dashboard

**Dashboard Preview:**
[View Dashboard Image](YOUR_DASHBOARD_IMAGE_LINK)

**Power BI Dashboard:**
[View Interactive Dashboard](YOUR_POWER_BI_LINK)

## Key Insights

* **Skip behaviour is strongly linked to playback issues:** Upload-related errors (**15%**) and track errors (**13%**) are the two largest skip drivers, suggesting technical/content availability issues can significantly affect engagement.

* **Listening engagement peaked around 2020–2021:** Plays reached approximately **55K**, before declining in the following years, indicating a major shift in listening activity over time.

* **Desktop users show stronger attention:** Desktop has a **74% attention rate vs. 50% on mobile**, suggesting users tend to engage more deeply with music on larger-screen devices.

* **Listening is concentrated among a few artists:** The Beatles account for **336+ hours** of listening time, followed by The Killers with **294+ hours**, showing a strong preference for a small group of artists.

* **Completion leaves room for improvement:** With a **52% completion rate**, nearly half of played tracks are not fully completed, creating an opportunity to investigate what drives early exits.

* **End-of-week listening is strongest:** Friday records the **highest listening activity**, indicating that listening engagement increases toward the end of the workweek.

## 💡 What I Learned

Gemini AI in Google Sheets helped me **reduce tedious data cleaning and analysis time**, allowing me to focus more on extracting insights. I then imported the prepared data into Power BI for **DAX calculations and interactive visualisation**.
