# 📋 Resume on dashboard

RMarkdown-based resume dashboard implemented in both static (flexdashboard) and interactive (Shiny) versions, allowing dynamic filtering of experience and interactive word cloud visualization.

This project demonstrates how personal CV data can be repurposed as a structured dataset for interactive analytics and visualization.

## 🎯 Aim

To design an interactive R-based CV dashboard that demonstrates
- how structured career data can be dynamically filtered by time and
- analysed using text-mining techniques such as word frequency and word cloud generation.
    
## ⚙️ Methods

Interactive timeline visualization and text mining–based word cloud generation implemented in R (flexdashboard + Shiny).

## 🔄 Analytical workflow

- Data preparation - structured datasets were created to capture education, professional experience, training activities, projects, and technical skills. Each record included relevant data such as start and end dates, organization, role, and additional descriptive information
- Dashboard design - the overall dashboard structure and user experience were planned, including the organization of content into timelines, summary tables, and visualizations
- Interactive timeline development - timelines were generated in R to visualize career progression. Static visualizations were enhanced with Plotly to enable interactive exploration
- Text mining and word cloud generation - textual information from the datasets was processed to calculate word frequencies, which were subsequently visualized as word clouds to highlight dominant themes and competencies
- Tabular data presentation - the underlying datasets were converted into interactive DataTables and organized into tabbed sections, allowing detailed exploration of education, experience, training, projects, and skills
- Shiny application development - the dashboard was extended into a Shiny application by introducing a sidebar with user-controlled filters. Users can dynamically select the time period of interest and define the minimum word frequency displayed in the word cloud
- Reactive programming and visualization - custom filtering functions were implemented to update datasets based on user input. Reactive outputs were created using renderPlotly() and renderDataTable() to ensure that visualizations and tables respond automatically to filtering selections
- Deployment - The completed application was deployed to ShinyApps.io, making the interactive dashboard accessible through a web browser without requiring a local R environment

## 💡 Output:

- [Static dashboard](https://anna-mal.github.io/Resume/Resume_Timeline.html#timelines-wordclouds)
- [Interactive dashboard](https://g6q0jb-anna-malinowska.shinyapps.io/Resume_Timeline_shiny/)
- [Code](https://github.com/Anna-Mal/Resume)
