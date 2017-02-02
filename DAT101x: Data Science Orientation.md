# Data Science Orientation

### Module 2: DS Fundamentals
What can data tell: descriptive, associative, comparative, predictive
What Excel can bring us simple visualization: Conditional Formatting -> Color Scales; Insert -> Line; PivotTable & PivotChart

<hr/>
### Module 3: Basic Statistics
* standard error (SE) = sample standard variance / sqrt(sample size)
* Hypothesis Testing: <br/>
  **T-test** (df=n-1) <br/>
  ![ALT TEXT](https://wikimedia.org/api/rest_v1/media/math/render/svg/1063f91f450e9fd0094a38f1856eb11bd201d232)<br/>
  **Two-Sample T-Tests** (df=n1+n2-2)<br/>
  Equal or unequal sample sizes, equal variance<br/>
  ![ALT TEXT](https://wikimedia.org/api/rest_v1/media/math/render/svg/faf70034d0a3a686080b98b32f64f2cc62a5dbad)<br/>
    Equal sample sizes, equal variance<br/>
  ![ALT TEXT](https://wikimedia.org/api/rest_v1/media/math/render/svg/cad0574bf2031d40d0194bfbe427567367aab4a8)<br/>
  **Paired T-Tests** (df=n-1)<br/>
    When the samples are dependent, compare current values with historical values, or compare experimental values with control<br/>
  ![ALT TEXT](https://wikimedia.org/api/rest_v1/media/math/render/svg/18eb62b7eb006088cfff7c9cbc58b718cf8dbd51)<br/>

What Excel can bring us for statistical analysis:
  1. Option -> Add-in -> Analysis ToolPack + VBA Pack
  2. Data -> Analysis -> Data Analysis -> Descriptive Statistics/Correlation/t-Test/ANOVA(Analysis of variance)/Regression
  3. Formula: Z.TEST(array, x, [sigma])
  
#### SOME ANOVA FACTS
Analysis of variance (ANOVA) is used to simultaneously test for differences between the means of two or more independent groups (many sources state that the minimum is three, but it can be used with two although it should be noted that this is technically a t-test). In the case of ANOVA, group membership is the “treatment” condition (also known as the “independent variable”) and is a categorical variable. The outcome of interest (known as the “dependent variable” because the result ‘depends’ on group membership) must be a continuous variable.

<hr/>
Check out [THIS LINK](https://github.com/MicrosoftLearning/Data-Science-Orientation/raw/master/Data%20Science%20101%20Statistics%20Overview.pdf) for more insights of statistics.

Some distribution [Tables](http://documents.software.dell.com/Statistics/Textbook/Distribution-Tables).