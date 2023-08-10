# US Domestic Airline Performance and Delay Analysis Dashboard
## Introduction

The US Domestic Airline Flights Performance Dashboard, built using Python's Dash framework, offers an interactive web experience. It facilitates a comprehensive understanding of US domestic airline performance and delays. By visualizing key data trends, users gain insights into airline operations, aiding informed decisions within the aviation industry.

## Methodology

This dashboard employs Dash to create an intuitive web interface for data visualization:

### Data Collection: Relevant US domestic airline flights data is sourced from a public dataset, covering flight details, cancellations, and delays.

### Data Preprocessing: Collected data undergoes cleaning, transformation, and organization, ensuring suitability for analysis.

### Dashboard Design: The Dash framework is employed to design the web application's layout. HTML components are used to structure the dashboard interface, including titles, dropdown menus, and graph placeholders.

### Interactive Components: Dropdown menus are implemented using Dash's dcc.Dropdown component, allowing users to select report types and specific years. These inputs serve as triggers for generating and updating the visualizations.

### Callback Functions: Callback functions are defined to handle user inputs and dynamically generate graphs based on the selected options. These functions utilize the Pandas library for data manipulation and Plotly for creating interactive graphs.

### Graph Generation: The application offers two main report types: Yearly Airline Performance Report and Yearly Airline Delay Report. For each report type, the relevant data is processed and visualized using various types of graphs, such as bar charts, line plots, and pie charts.

### Deployment: The Dash application is run locally using the app.run_server() method, making it accessible through a web browser. Users can interact with the dashboard, exploring different aspects of airline performance and delays.
