# 📄 Resume Analyzer Pro (AIDS Project)

## 📌 Introduction

Resume Analyzer Pro is an interactive resume analysis and resume-building application developed using R Shiny under the Artificial Intelligence and Data Science (AIDS) domain.

The project helps users analyze resumes by identifying skills, experience, education details, and overall resume strength using dashboards and visualizations.

---

## 🎯 Objective

- Analyze resumes intelligently
- Match resumes with job roles
- Identify missing and existing skills
- Generate visual insights
- Help improve resume quality
- Provide resume-building functionality

---

## ⚙️ Technologies Used

- R Programming
- Shiny
- shinydashboard
- ggplot2
- wordcloud
- pdftools
- tm
- fmsb

---

## 🚀 Features

- Upload resume in PDF or TXT format
- Resume text extraction and preprocessing
- Role-based skill analysis
- Resume scoring system
- Skills found vs missing skills analysis
- Interactive charts and visualizations
- Word cloud generation
- Resume links detection
- Download analysis reports
- Resume Builder with live preview
- Download resume as TXT file

---

## 📊 Dashboard Modules

### Upload Section

- Upload resume file
- Select target role
- Analyze resume instantly

### Dashboard Analysis

- Resume score
- Skills found and missing
- Bar chart and pie chart
- Radar chart
- Experience analysis
- Education timeline
- Word cloud visualization
- Recommendations and tips

### Reports Section

- Download resume analysis
- View summary reports

### Settings

- Theme selection
- Save analysis preferences

### Resume Builder

- Create professional resume
- Add skills, experience, education, and projects
- Live resume preview
- Download resume

---

## 📊 Methodology

1. Upload resume file
2. Extract text from resume
3. Clean and preprocess data
4. Match skills with selected role
5. Calculate resume score
6. Generate charts and visualizations
7. Display recommendations
8. Build and download resume

---

## ▶️ How to Run the Project

### Install Required Packages

```r
install.packages(c(
  "shiny",
  "shinydashboard",
  "ggplot2",
  "wordcloud",
  "tm",
  "RColorBrewer",
  "stringr",
  "pdftools",
  "fmsb"
))
```

### Run the Application

```r
shiny::runApp("app.R")
```

or

```r
runApp()
```

---

## 📁 Project Structure

```text
Resume-Analyzer-Pro/
│
├── app.R
├── README.md
└── resume.text.pdf
```

---

## 📈 Supported Roles

- Data Analyst
- Data Scientist
- Web Developer

---

## 📷 Output

- Interactive dashboard
- Resume analysis score
- Skills insights
- Visual reports and charts
- Resume preview and downloadable resume

---

## 💡 Key Visualizations

- Bar Chart
- Pie Chart
- Radar Chart
- Word Cloud
- Experience Chart
- Education Timeline

---

## 👩‍💻 Author

Sanika Mendhe

---

## 📌 Conclusion

Resume Analyzer Pro converts resume data into meaningful visual insights. It helps users improve resumes, identify missing skills, and build professional resumes effectively using data analysis and visualization techniques.

```
