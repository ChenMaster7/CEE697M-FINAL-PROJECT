# Final-Project---CEE-697M
### Aniruddha Prasad, Jerry Chen

## Introduction:


As two students from very different ethnic and socioeconomic backgrounds, we have decided to tackle a subject that needs to have more light shined on it: Teaching styles and their influences on the learning process and test scores of a diverse set of students.
We believe that it is important that children, regardless of their background, should receive the same quality of education and hence get the same opportunities as their peers who might be better off socioeconomically.

## Objectives:
- The objective is to analyze and predict the 8th-grade test scores, and recommend a specific teaching method – standards-based or traditional.
- Use teacher, socioeconomic, gender, and ethnic background to predict the score.
- Use score, socioeconomic, gender, and ethnic background to predict the teacher for verification.
- Analyze multiple combinations between the provided variables and analyze the trends.
- Use multiple models to develop a “master” model with the highest predictability.
- Utilize and learn the CNN and ANN process.

## Data:
For this project, we will be using the “Student’s Math Score for Different Teaching Styles” dataset from Kaggle.com. This breaks down a student’s math score, their ethnicity, socioeconomic status and the teacher that they are being taught by. There are three teachers in this dataset: Ms. Ruger, a young African-American women who is certified to teach science and math, Ms. Smith, a Caucasian lady in her 40s who is certified to teach Spanish and math and Ms. Wesson, an older Caucasian lady who has been teaching PE for 24 years but has been assigned to teach math for the last 3 years.
Each teacher is allowed to choose their own textbook and teaching styles.
Ruger and Smith follow a teaching method that can be defined as the standards-based method. Under this method, the teacher is there to facilitate the learning in a constructivist environment so that students can develop, explore, conjecture and test their conjectures within the confines of the standard. The teacher believes there is research that a majority of children learn more and deeper mathematics and are better problem solvers when in the standards-based classroom.1
Wesson follows a teaching method that can be defined as the traditional method. Under this method, the teacher adheres to a top-down approach in which knowledge originates from the
1 Das, S. (2022, February 23). Student's math score for different teaching style. Kaggle. Retrieved April 11, 2022, from https://www.kaggle.com/datasets/soumyadiptadas/students-math-score-for-different-teaching-style teacher and is disseminated to the students. Traditional teachers tend to thrive on structure and order, resulting in calm learning environments. The teacher believes there is research that indicates certain behavioral issues are minimized in a traditional classroom resulting in effective, direct instruction.

## Methods:

The methods we plan to use for this project are: GAM (linear), ANN (nonlinear), Random Forest Regressor.
Each method produces a slightly different model that accounts for overfitting, bias, variance,
- GAM vs ANN
- GAM provides a linear prediction model, which
- ANN provides a nonlinear prediction model, which may predict an overfitted prediction.

## Results:

We have summarized the expected results below:
- Expect higher performance with the standard-based method
- Expect higher performance with better socioeconomic status.
  - Paid lunch = better socioeconomic status = higher score
  - Worse socioeconomic status may indicate more responsibilities at home, preventing students from spending enough time to properly learn.
- Expect students who are underprivileged and not Caucasian to perform worse under Wesson when compared to the other teachers.
- Expect female students from worse socioeconomic to perform poorly when compared to their male counterparts.
  - Families of lower socioeconomic statuses may have more traditional views on gender roles and expect the females to be more involved in household duties, impacting their ability to perform well in school.
- Measure and compare performances between GAM and ANN methods.
  - Mean absolute error (MAE)
  - Mean squared error (MSE)
  - 𝑅2 value
  - Random forests and out-of-bag (OOB) score
 
https://prod.liveshare.vsengsaas.visualstudio.com/join?D72E7F2FD15A8344BFC02261CA2ACA6A8C69
https://www.kaggle.com/datasets/soumyadiptadas/students-math-score-for-different-teaching-style
