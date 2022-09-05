# Students_Performance_in_Exam_Exploration

## Dataset

This dataset consist of the marks secured by the students in various subjects, including their gender, race/ethnicity, lunch, and test preparation course. this dataset can be found this Kaggle notebook [here.] (https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)


## Summary of Findings

In the exploration, I found that all the scores were centainly highly corelated with a linear relationship. And so was percentage with all the score variables. - No transformations were required to prove this. Female students performed well compared to male students, but interestingly outliers were more for female students in the lowest grade than compared to the male students. As expected, students who completed the test preparation course, had high percentages as compared to the students who didn't complete the test preparation course. finally, Students who got standard lunch perform much better than students who had free/reduced lunch

## Key Insights for Presentation

I extended my investigation by plotting all the scores in a single scatter plot and as expected, the correlation is high. Then I plotted a PairGrid plot for numeric values segregated by gender only to prove that female students overall have done better than male students.
After that, I plotted a pairplot for numeric values segregated by test_preparation_course only to prove that students who have completed the test preparation course have done way better than those who haven't. Later, I concluded with a barplot for both qualitative variable with percentage only to prove what's stated above.