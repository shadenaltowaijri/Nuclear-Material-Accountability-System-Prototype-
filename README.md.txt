Nuclear Material Accountability System (Prototype)


Overview
This project is a data-driven prototype that simulates a simplified nuclear material tracking and monitoring system.
It aims to enhance regulatory transparency and radiation safety by detecting imbalances between material inflows and outflows across different facilities.




Objectives
Monitor nuclear material movement across multiple facilities.
Automatically detect discrepancies in recorded quantities.
Identify facilities that require inspection based on abnormal activity.
Provide data-driven insights and visual reports for decision-makers.




Methodology
Data Validation – Loading and cleaning facility records.
Mass-Balance Calculation – Comparing inflow (Quantity_in) and outflow (Quantity_out).
Automated Flagging – Detecting anomalies using dynamic thresholds per material type.
Visualization – Graphical representation of flagged records and imbalance patterns.
Summary & Recommendations – Highlighting problem areas and proposing process improvements.




Results
Facilities with abnormal differences are automatically flagged (Flag = "CHECK").
The system identified specific materials (e.g., Uranium-235, Cesium-137) with higher imbalance rates.
The analysis supports early detection of reporting or measurement errors.




Future Development
A planned enhancement is to transform this prototype into an intelligent early-warning system that automatically generates real-time alerts when abnormal activity is detected.

This will include:
Severity classification (minor / moderate / critical)
Dashboard integration with alert notifications
Real-time streaming for continuous monitoring




Technologies Used
Python
Pandas – Data manipulation and analysis
Matplotlib – Visualization
NumPy – Numerical computation




Author
Shaden Altowaijri
Developed as part of an independent project exploring AI-driven monitoring and data analytics for regulatory safety applications.