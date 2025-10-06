## Functional Requirements

| ID   | Functional Requirements        | Acceptance Criteria                                                                 |
|------|--------------------------------|-------------------------------------------------------------------------------------|
| RF01 | Main Screen with Charts (Dashboard) | Dashboard will follow these specifications:<br> - will be the user's home screen <br> - option to filter time interval <br> - will be composed of the charts/items described in requirements RF02, RF03, RF05, RF06, and RF07 |
| RF02 | Score Critical Applications | Bar chart:<br> - products with the highest number of tickets <br> - x-axis will have the product names, y-axis the number of tickets <br> - when clicking on a bar, it will display the ticket categories for that product |
| RF03 | View Ticket Evolution           | Line chart:<br> - evolution over the months for each ticket category <br> - x-axis will be time (in months), y-axis the number of tickets <br> - one line for each category <br> - field for the user to insert start and end dates, so the chart shows the specified interval <br> - show the percentage that each category represents when hovering over the nodes of each line |
| RF04 | Access Management               | Access management:<br> - two types of users: admin with access to the registration screen, analyst/decision maker with access to dashboards |
| RF05 | Overdue Tickets                   | Card:<br> - number of overdue tickets (not resolved within the agreed SLA time) <br> - take the present time into account. |
| RF06 | Highlight Critical Sub-Categories | Pie chart:<br> - most frequent ticket sub-categories <br> - each slice of the chart will represent the percentage of tickets in that sub-category relative to the total |
| RF07 | Average Resolution Time   | Card:<br> - average resolution time of the tickets <br> - consider the time range defined by the user on the screen to calculate the average  |
| RF08 | Score of unhappy clients   | Table:<br> - ranking with the top 4 unhappy clients <br> - client satisfaction will be assessed based on quantitative and qualitative data  |
| RF09 | Screen with clients satisfaction levels   | Dashboard:<br> - option to filter by client and project <br> - charts that display customer satisfaction and project performance|
