# Excel Task Performance Analysis - Portfolio Project

A polished, Excel-based project management and financial analysis dashboard designed to showcase my ability to turn data into clear, actionable insights for cross-functional teams and leadership.

## Project overview
This project demonstrates a real-world dashboard built in Excel that tracks departmental tasks, budgets, timelines, and performance metrics. It is intended as a portfolio piece for recruiters and hiring managers to see how I structure data and create visualizations that drive decision-making.

Snapshots from the dashboard:
 <img width="528" height="393" alt="{DD645A44-06C4-43D7-8C1D-7C678D2A0280}" src="https://github.com/user-attachments/assets/c43895b3-9189-4599-8f56-0305d6d2b1b0" />


 <img width="526" height="391" alt="{540B4EC9-438C-476C-B470-2EDF6ADAC52B}" src="https://github.com/user-attachments/assets/0a9fa760-86e3-4269-a1a7-09d28920e240" />


## Key features
- Project management across Finance, HR, IT, and Admin with clear task ownership
- Real-time status indicators and conditional formatting for quick triage
- Budget tracking and variance analysis to flag over- and under-spending
- Performance analytics including completion rates, days remaining, and resource vs. budget comparisons
- Interactive controls: dropdowns for department, status, and priority to keep the model consistent and user-friendly
- Visualizations for budget variance and completion percentage to support executive reporting

## Project tasks tracked
| Department | Task | Status | Priority | Budget | Completion |
|-----------|------|--------|----------|--------|------------|
| Finance | Prepare Q2 Report | In Progress | High | $4,500 | 65% |
| HR | Update Employee Records | Completed | Medium | $1,200 | 100% |
| IT | System Maintenance | Delayed | High | $7,800 | 40% |
| Admin | Office Supply Audit | Completed | Low | $350 | 100% |
| Finance | Budget Forecasting | In Progress | High | $5,200 | 50% |
| HR | Training Session Prep | Not Started | Medium | $900 | 0% |
| IT | Software Updates | In Progress | High | $3,600 | 20% |
| Admin | Meeting Coordination | Completed | Low | $150 | 100% |

## Key findings
- Total budget allocated across tracked tasks: $23,700
- Completed: 3 projects; In Progress: 3 projects; Delayed: 1 project; Not Started: 1 project
- Average completion rate across active initiatives: 59.38%
- Four high-priority tasks require focused attention; one high-priority IT task is delayed and flagged for intervention
- Several projects show negative days remaining — an early warning to re-evaluate timelines or reallocate resources

## Visualizations highlights
- Priority-based color coding (High/Medium/Low) to surface urgent items
- Status indicators: Green = Completed, Yellow = In Progress, Red = Delayed, and Gray = Not Started
- Budget variance charts that update when actuals are entered, enabling quick identification of over-budget items
- Completion percentage gauges and timeline views to show progress at-a-glance

## Technical implementation
Excel features and techniques used:
- Core formulas: SUMIF, COUNTIF, and conditional aggregation to produce dynamic KPIs
- Conditional formatting: Custom rules to color-code status and priority
- Data validation: Dropdown lists to enforce consistent labels for department, status, and priority
- Charts & visualizations: Bar and column charts for budget and completion analysis
- Automation: Formula-driven 'Days Remaining' counters and over-Budget flags for proactive alerts

### Key formulas
- Completion rate: Calculated as completed work / total planned work (dynamic based on status and percent-complete)
- Budget variance: Allocated budget − actual spend (with conditional formatting to highlight negative variance)
- Days remaining: due date − Current date in file (automated countdown)
- Over-budget detection: Conditional checks that flag any task where actual > allocated

## Skills demonstrated
- Advanced data analysis using Excel to support business decisions
- Strong attention to detail in chart design
- Ability to present financial and project status clearly for non-technical stakeholders
- Cross-functional coordination: one view that reflects Finance, HR, IT, and Admin needs

## Use cases
- Project managers can monitor multi-department initiatives and allocate resources
- Finance teams: Track spending, detect variance, and forecast budgets
- Executive leadership to quickly assess project health
- Department head can manage assignments and ensure deadlines are met
