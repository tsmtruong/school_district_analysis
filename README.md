# School District Analysis

## Overview of Project

### Purpose

The purpose of this analysis was to provide a snapshot of certain key metrics of schools within the district and the district as a whole for the school board members. The analysis focused on math and reading scores as well as passing percentages for those subjects, overall passing percentages, school size, school budgets and how the latter two related to the passing percentages. As issues arose within grade 9 of Thomas High School those results were then omited for the final analysis.
## Results
- How is the district summary affected?
![Original District Summary](https://github.com/tsmtruong/school_district_analysis/blob/main/Resources/district%20summary%20original.jpg)
![Adjusted District Summary](https://github.com/tsmtruong/school_district_analysis/blob/main/Resources/district%20summary%20adjusted.jpg)
    When comparing the two images the changes from the original district summary and the adjusted district summary is very small. The changes to the entire distirct when adjusted has basically no impact on any of the scores due to the size of the initial sample.

- How is the school summary affected?
![Original School Summary](https://github.com/tsmtruong/school_district_analysis/blob/main/Resources/school%20summary%20original.jpg)
![Adjusted School Summary](https://github.com/tsmtruong/school_district_analysis/blob/main/Resources/school%20summary%20adjusted.jpg)
    As opposed to the district summary there was a large change in the school summary. In comparison to the original summary that showed an overall pass rate of almost 91% the new adjusted summary shows a much lower overall rate of 65%. The removal of the 9th grade test scores proved to be detrimental to Thomas High School.
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
![Top 5 Original](https://github.com/tsmtruong/school_district_analysis/blob/main/Resources/top%20schools%20original.jpg)
![Top 5 Adjusted](https://github.com/tsmtruong/school_district_analysis/blob/main/Resources/top%20schools%20adjusted.jpg)
    When completely removing the 9th graders from the equation the ranking of Thomas High School stayed the same, if anything they performed nominally better than previously. This is the results with the 9th graders completely removed, however, if you were to keep the count of the 9th graders count in but removed the scores Thomas High School would be towards the middle or bottom of the list
- How does replacing the ninth-grade scores affect the following:
- Math and reading scores by grade
![Math Scores Original](https://github.com/tsmtruong/school_district_analysis/blob/main/Resources/math%20scores%20by%20grade%20original.jpg)
![Math Scores Adjusted](https://github.com/tsmtruong/school_district_analysis/blob/main/Resources/math%20scores%20by%20grade%20adjusted.jpg)

Other than the removal of the 9th grade scores to show NaN there was no other changes to the math or reading scores upon removal/replacing the 9th grade test scores at Thomas High School.

![Reading Scores Original](https://github.com/tsmtruong/school_district_analysis/blob/main/Resources/reading%20scores%20by%20grade%20original.jpg)
![Reading Scores Adjusted](https://github.com/tsmtruong/school_district_analysis/blob/main/Resources/reading%20scores%20by%20grade%20adjusted.jpg)
    
    - Scores by school spending


![School Spending Original](https://github.com/tsmtruong/school_district_analysis/blob/main/Resources/Scores%20by%20Spending%20Original.jpg)
![School Spending Adjusted](https://github.com/tsmtruong/school_district_analysis/blob/main/Resources/scores%20by%20spending%20adjusted.jpg)

    Due to the vast size of the analysis the removal of the Thomas High School 9th grade test scores showed very slight changes to spending, school size, and school type. These changes wouuld be negated once rounded and would not show any noticable differences. 

    - Scores by school size



![School Size Original](https://github.com/tsmtruong/school_district_analysis/blob/main/Resources/Scores%20by%20size%20original.jpg)

![School Size Adjusted](https://github.com/tsmtruong/school_district_analysis/blob/main/Resources/scores%20by%20size%20adjusted.jpg)


    - Scores by school type

![School Type Original](https://github.com/tsmtruong/school_district_analysis/blob/main/Resources/scores%20by%20type%20original.jpg)


![School Type Adjusted](https://github.com/tsmtruong/school_district_analysis/blob/main/Resources/scores%20by%20type%20adjusted.jpg)



## Summary

The four major changes found after the 9th grade test scores were replaced  were. The school's overall passing rate plummeted to 65% from just shy of 91%. When including the count of 9th grade test scores Thomas High School's ranking dropped significantly in the district, however if you were to completely remove the 9th graders from the equation their ranking stayed the same if anything they performed slightly better than they did with the 9th grade scores. When replacing the 9th grade test scores the score not show up on reports as NaN as opposed to a number as they are no longer counted as numbers. Lastly while the changes were slight the overall math and reading percentages saw a shift in either direction.
