<div align="center">
  
  # 🎓 Student Results Analysis System
  
  [![Python](https://img.shields.io/badge/Python-3.6%2B-blue?style=for-the-badge&logo=python)](https://python.org)
  [![SQLite](https://img.shields.io/badge/SQLite-3-green?style=for-the-badge&logo=sqlite)](https://sqlite.org)
  [![Pandas](https://img.shields.io/badge/Pandas-1.3%2B-purple?style=for-the-badge&logo=pandas)](https://pandas.pydata.org)
  [![Matplotlib](https://img.shields.io/badge/Matplotlib-3.4%2B-orange?style=for-the-badge&logo=matplotlib)](https://matplotlib.org)
  [![License](https://img.shields.io/badge/License-MIT-red?style=for-the-badge)](https://opensource.org/licenses/MIT)

  <h3>A powerful Python application for analyzing student academic performance</h3>
  
  [🚀 Features](#-features) • [📦 Installation](#-installation) • [💻 Usage](#-usage) • [📊 Reports](#-reports) • [🤝 Contributing](#-contributing)
  
  <img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">
</div>

## ✨ Features

<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="https://img.icons8.com/color/48/000000/database.png" width="40"/>
        <br/>
        <b>SQLite Database</b>
        <br/>
        <sub>Lightweight & portable</sub>
      </td>
      <td align="center">
        <img src="https://img.icons8.com/color/48/000000/data-configuration.png" width="40"/>
        <br/>
        <b>Mock Data</b>
        <br/>
        <sub>Automatic generation</sub>
      </td>
      <td align="center">
        <img src="https://img.icons8.com/color/48/000000/combo-chart.png" width="40"/>
        <br/>
        <b>Visual Reports</b>
        <br/>
        <sub>PNG & Excel formats</sub>
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="https://img.icons8.com/color/48/000000/statistics.png" width="40"/>
        <br/>
        <b>Statistical Analysis</b>
        <br/>
        <sub>Grades & averages</sub>
      </td>
      <td align="center">
        <img src="https://img.icons8.com/color/48/000000/csv.png" width="40"/>
        <br/>
        <b>CSV Export</b>
        <br/>
        <sub>Easy data sharing</sub>
      </td>
      <td align="center">
        <img src="https://img.icons8.com/color/48/000000/microsoft-excel.png" width="40"/>
        <br/>
        <b>Excel Reports</b>
        <br/>
        <sub>Multiple sheets</sub>
      </td>
    </tr>
  </table>
</div>

## 🏗️ Database Schema

```mermaid
erDiagram
    STUDENTS ||--o{ RESULTS : has
    COURSES ||--o{ RESULTS : contains
    
    STUDENTS {
        int id PK
        string name
        string department
        int enrollment_year
    }
    
    COURSES {
        int id PK
        string name
        string department
    }
    
    RESULTS {
        int student_id FK
        int course_id FK
        float marks
    }
