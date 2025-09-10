## Functional Requirements

| ID   | Functional Requirements        | Acceptance Criteria                                                                 |
|------|--------------------------------|-------------------------------------------------------------------------------------|
| RF01 | Main Screen with Charts (Dashboard) | Dashboard will follow these specifications:<br> - will be the user's home screen <br> - will be composed of the charts/items described in requirements RF02, RF03, RF05, RF06, and RF07 |
| RF02 | Highlight Critical Applications | Bar chart:<br> - products with the highest number of tickets <br> - x-axis will have the product names, y-axis the number of tickets <br> - when clicking on a bar, it will display the ticket categories for that product |
| RF03 | View Ticket Evolution           | Line chart:<br> - evolution over the months for each ticket category <br> - x-axis will be time (in months), y-axis the number of tickets <br> - one line for each category <br> - field for the user to insert start and end dates, so the chart shows the specified interval |
| RF04 | Access Management               | Access management:<br> - two types of users: admin with access to the registration screen, analyst/decision maker with access to dashboards |
| RF05 | Ticket Status                   | 4 Cards with the following information:<br> - overdue tickets (not resolved within the agreed SLA time)<br> - tickets opened today <br> - tickets resolved today <br> - average resolution time for tickets |
| RF06 | Highlight Critical Sub-Categories | Pie chart:<br> - most frequent ticket sub-categories <br> - each slice of the chart will represent the percentage of tickets in that sub-category relative to the total |
| RF07 | Highlight Latest Open Tickets   | Table:<br> - related to the latest critical open tickets <br> - 4 columns with the following data: client name, product name, date, and sub-category |