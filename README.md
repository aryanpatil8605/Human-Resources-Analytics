# HR Dashboard Project 

## Project Overview

This HR dashboard was designed to monitor key employee metrics that are critical for workforce planning and talent management. The dashboard tracks:
- Employee retention and headcount trends
- Productivity and satisfaction scores
- Workforce diversity metrics

The dashboard provides HR teams with a visual summary of employee data, enabling informed decision-making to support retention, improve employee satisfaction, and maintain a balanced workforce.

---

## Data Source

The data used in this dashboard contains the following columns:
1. **Employee_ID**: Unique identifier for each employee
2. **Department**: The department each employee is assigned to (Finance, HR, IT, Marketing, Sales)
3. **Satisfaction_Score**: Employee’s satisfaction level on a scale of 1 to 5
4. **Performance_Score**: Employee’s performance level on a scale of 1 to 5
5. **Gender**: Gender of each employee

---

## Dashboard Components

### 1. Sum of Performance Score by Department (Pie Chart)

**Description**: This pie chart shows the total Performance Score for each department, providing insight into how departments are performing relative to each other.

**Purpose**: Helps identify departments with high or low performance, potentially highlighting areas where additional support may be needed.

---

### 2. Sum of Satisfaction Score by Department (Bar Chart)

**Description**: This bar chart displays the cumulative Satisfaction Score per department, giving an overview of how satisfied employees are across different departments.

**Purpose**: Highlights satisfaction trends by department, allowing HR to focus on departments with lower satisfaction scores for improvement initiatives.

- **X-Axis**: Department names (HR, IT, Marketing, Finance, Sales)
- **Y-Axis**: Sum of Satisfaction Scores

---

### 3. Count of Employee_ID by Department (Scrollable List)

**Description**: This component shows the number of employees in each department.

**Purpose**: Provides a quick reference for headcount in each department, which is useful for understanding department sizes and comparing against performance or satisfaction metrics.

---

### 4. Count of Gender by Gender (Pie Chart)

**Description**: A pie chart that displays the gender distribution of employees across the organization.

**Purpose**: Useful for diversity tracking, as it shows the percentage of employees by gender, which helps in evaluating gender representation in the company.

---

### 5. Sum of Satisfaction Score (Donut Chart)

**Description**: This donut chart shows the total Satisfaction Score across all departments.

**Purpose**: This is an at-a-glance indicator of overall employee satisfaction in the company.

---

### 6. Sum of Performance Score by Satisfaction Score and Department (Stacked Bar Chart)

**Description**: This stacked bar chart visualizes the relationship between Satisfaction Scores and Performance Scores, segmented by department.

**Purpose**: This chart provides deeper insights into how employee satisfaction correlates with performance, broken down by department, which helps HR understand areas with strong satisfaction-performance alignment.

- **X-Axis**: Satisfaction Score (1 to 5)
- **Y-Axis**: Sum of Performance Scores, broken down by Department (Finance, HR, IT, Marketing, Sales)

---
![{5217ED8C-7B90-47CB-B0F2-C47B0DF1BB58}](https://github.com/user-attachments/assets/ae45bbb9-9804-43e5-b03c-84ad1f194f36)

## Analysis & Insights

Using this dashboard, the HR team can derive valuable insights:

- **Department Performance**: By comparing performance scores across departments, HR can identify areas for improvement and departments that are high-performing.
- **Satisfaction Levels**: Satisfaction scores across departments can reveal departments with lower morale or engagement, prompting targeted HR interventions.
- **Diversity Analysis**: Gender distribution can be used to ensure diversity in the workforce and address any gender imbalances.
- **Retention Indicators**: Satisfaction and performance correlations can be early indicators of employee retention, helping HR to proactively address any potential issues.

---

## Future Enhancements

For future iterations, consider adding the following:

- **Tenure**: Add tenure data to understand satisfaction and performance trends relative to employee tenure.
- **Age & Education**: Include age and education level for a more detailed diversity analysis.
- **Trends Over Time**: Implement time-series analysis to track satisfaction and performance changes over time.

---

## Conclusion

This HR dashboard provides a comprehensive, data-driven approach to workforce management, helping HR make decisions that improve employee satisfaction, productivity, and diversity. The visualizations simplify complex data, enabling quick insights for effective workforce planning.

---
