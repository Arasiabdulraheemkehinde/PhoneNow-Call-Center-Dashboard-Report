# 📞 PhoneNow Call Center Dashboard Report

## I. Introduction

### Brief Overview of the Dashboard
The **PhoneNow Call Center Dashboard** provides a visual summary of the key metrics related to call center performance from **January 2021 to March 2021**. It helps stakeholders assess agent performance, customer satisfaction, and operational efficiency using real-time call data. The dashboard also highlights common customer concerns to aid in resource allocation.

### Problem Statement Addressed
The key challenge addressed is understanding customer satisfaction levels, agent performance, and identifying frequently raised issues. This enables PhoneNow to reduce abandonment rates, improve resolution effectiveness, and elevate service quality.

### Objectives
- Monitor and evaluate customer satisfaction levels.
- Track call center agent performance in handling/resolving calls.
- Identify recurring customer concerns and discussion topics.
- Provide actionable insights to improve service and operational efficiency.

---

## II. Data Description

### Data Source
The dataset was sourced from **PhoneNow Call Center Records**, containing the following fields:
- `Call ID`
- `Agent Name`
- `Date and Time of Calls`
- `Topic`
- `Answered (Y/N)`
- `Resolved (Y/N)`
- `Speed of Answer (seconds)`
- `Average Talk Duration`
- `Customer Satisfaction Rating`

### Data Cleaning & Preprocessing
1. **Missing Values**: Filled or flagged missing data in key fields.
2. **Data Type Correction**: Ensured correct formatting for dates, numbers, and categories.
3. **Aggregation**: Grouped by month and topic to analyze trends.
4. **Outlier Treatment**: Flagged extremely long calls or low satisfaction scores.

### Data Visualization Strategy
An interactive and user-friendly dashboard was built using:
- Bar charts for comparisons
- Cards for KPIs
- Gauge chart for customer satisfaction score
- Filters for Agent, Date, and Topic

---

## III. Dashboard Design

### UX Considerations
- **Simplicity**: Color-coded visuals for quick interpretation.
- **Interactivity**: Filters for agent and date for customized insights.
- **Responsiveness**: Dynamic visuals update based on user selections.

### Key KPIs Tracked
1. **Total Calls**: ~5,000 calls
2. **Answered vs Abandoned**: 4,000 answered, 946 abandoned
3. **Average Speed of Answer**: 67.52 seconds
4. **Resolution Rate**: Monthly trend of resolved/unresolved
5. **Customer Satisfaction Rating**: Avg score of 3.40 (target = 4.0)
6. **Top Topics**: Streaming & tech support dominate discussions

---

## IV. Technical Implementation

### Tools Used
- **Microsoft Power BI**
- **DAX (Data Analysis Expressions)** for KPI calculations

### Best Practices
- **Color Coding**: Navy blue (positive), green (negative)
- **Minimal Clutter**: Simple visuals for quick insights
- **Gauge Chart**: Satisfaction score with benchmarks

### Interactive Elements
- Date range filter
- Agent performance filter
- Topic-level insights

---

## V. Insights & Findings

### Key Patterns Identified
1. **High Call Abandonment**: 946 abandoned calls suggest long wait times.
2. **Moderate Satisfaction**: Avg score of 3.40 falls short of the 4.0 target.
3. **Frequent Topics**: Streaming & tech issues need focused support.
4. **Top Agent Performance**: Agents Jim and Dan outperform others.

### Recommendations
- Offer **callback options** and automate FAQs to reduce abandonment.
- Train agents on **streaming & technical topics**.
- Investigate low satisfaction drivers and improve resolution.
- Encourage top agents to share best practices with peers.

### Business Value
This dashboard empowers PhoneNow to streamline service, retain customers, and drive agent productivity by transforming raw data into actionable business intelligence.

---

## VI. Appendices

### Dashboard Screenshots
📸 See visuals in the `visuals/` folder.

### Data Dictionary
| Field | Description |
|-------|-------------|
| Call ID | Unique ID for each call |
| Agent | Agent handling the call |
| Date and Time | Timestamp of the call |
| Topic | Topic or issue discussed |
| Answered (Y/N) | Call status |
| Resolved (Y/N) | Whether the issue was resolved |
| Speed of Answer | Seconds taken to answer |
| Satisfaction Rating | Score (1 to 5) given by customer |

![Screenshot 2024-09-10 203357](https://github.com/user-attachments/assets/e823a51a-09e3-4998-85b1-e4ea6437cbf5)

