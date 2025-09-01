Graduation Project Analytics Dashboard
A comprehensive data analysis tool for tracking and visualizing graduation project progress, team performance, and student contributions.
📊 Overview
This project provides detailed analytics and visualizations for graduation project management, offering insights into team progress, task completion rates, meeting attendance, and student participation patterns.
🚀 Features

Team Progress Tracking: Monitor task completion rates across different teams
Task Status Analysis: Comprehensive breakdown of task statuses (completed, in-progress, pending)
Meeting Analytics: Track meeting attendance and frequency per team
Student Performance: Analyze individual student contributions and participation
Timeline Analysis: Visualize project progress over time
Completion Time Metrics: Analyze time taken to complete various tasks

📈 Visualizations
The dashboard includes several key visualizations:

Team Progress Chart: Bar chart showing completion rates for each team
Task Status Distribution: Pie chart displaying overall task status breakdown
Meeting Attendance: Stacked bar chart showing attendance patterns by team
Student Participation: Bar chart highlighting number of students per team
Meeting Frequency: Visual representation of meeting frequency across teams
Task Completion Timeline: Histogram showing distribution of task completion times
Top Contributors: Bar chart featuring top 10 students by task contributions
Individual Team Progress: Horizontal progress bar for specific team analysis
Cumulative Progress Over Time: Line chart tracking team progress evolution

📋 Data Requirements
The system expects a CSV file with the following columns:

team_id: Unique identifier for each team
member_id: Student member identifier
student_id: Individual student identifier
task_status: Status of tasks (completed, in-progress, pending)
task_created_at: Task creation timestamp
task_updated_at: Task last update timestamp
meeting.team_id: Team ID for meeting data
meeting.meeting_id: Unique meeting identifier
meeting_attendance_status: Attendance status for meetings

🛠️ Technologies Used

Python: Core programming language
Pandas: Data manipulation and analysis
Matplotlib: Primary plotting library
Seaborn: Statistical data visualization
Jupyter Notebook: Development environment

💻 Usage

Load your graduation project data into a CSV file named graduation_project_database.csv
Run the analysis script to generate all visualizations
Customize team selection by modifying the selected_team_id variable
Review generated charts and metrics for project insights

📊 Key Metrics
The dashboard tracks several important metrics:

Team completion rates
Task distribution by status
Meeting attendance rates
Student participation levels
Project timeline adherence
Individual student contributions

🔧 Customization
The visualizations can be easily customized:

Change color palettes by modifying the palette parameter
Adjust figure sizes using the figsize parameter
Select different teams for detailed analysis
Modify time periods for timeline analysis

📝 Output
The system generates:

Multiple visualization charts
Statistical summaries
Progress tracking metrics
Performance analytics
Team comparison data

🤝 Contributing
Contributions are welcome! Please feel free to submit pull requests or open issues for bugs and feature requests.
