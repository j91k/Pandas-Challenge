# PANDA-Challenge
## Introduction
This project utilized Pandas and Jupyter Notebook to analyze and report on a school district's performances based on various key metrics. The analysis included summaries and visualizations of data related to student performance, school spending, and other key factors. The report also highlighted observable trends within the data.
### Key Components of the Report
1. **District Summary:**
   - A high-level snapshot of the district's key metrics was created in a DataFrame. This summary included:
     - Total number of unique schools
     - Total students
     - Total budget
     - Average math score
     - Average reading score
     - Percentage of students passing math
     - Percentage of students passing reading
     - Percentage of students overall passing (both math and reading)
     
2. **School Summary:**
    - Detailed metrics for each school were calculated and presented in a DataFrame. This included:
    - School name
    - School type
    - Total students
    - Total school budget
    - Per student budget
    - Average math score
    - Average reading score
    - Percentage passing math
    - Percentage passing reading
    - Percentage overall passing
    
3. **Performance Ranking:**
    - Schools were ranked based on the overall passing percentage.
    - **Highest-Performing Schools:** The top 5 schools by overall passing percentage.
    - **Lowest-Performing Schools:** The bottom 5 schools by overall passing percentage.
    
4. **Scores by Grade:**
    - Analysis of average scores for math and reading by grade level (9th, 10th, 11th, 12th) at school.
    
5. **Scores by School Spending:**
    - Performance metrics were broken down based on school spending ranges per student. This included:
        - Average math score
        - Average reading score
        - Percentage of students passing math
        - Percentage of students passing reading
        - Overall passing percentage
    - Spending ranges were categorized into four bins for analysis:
        - <$585
        - $585-630
        - $630-645
        - $645-680
        
6. **Scores by School Size:**
    - Performance metrics were categorized based on the school size:
      - Small (<1000 students)
      - Medium (1000-2000 students)
      - Large (2000-5000 students)
    
7. **Scores by School Type:**
    - Analysis of school performance based on the type of school (district and charter)
