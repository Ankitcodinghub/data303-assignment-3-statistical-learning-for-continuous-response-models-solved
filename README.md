# data303-assignment-3-statistical-learning-for-continuous-response-models-solved
**TO GET THIS SOLUTION VISIT:** [DATA303 Assignment 3-Statistical Learning for Continuous Response Models Solved](https://www.ankitcodinghub.com/product/data303-assignment-3-statistical-learning-for-continuous-response-models-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;101395&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;DATA303 Assignment 3-Statistical Learning for Continuous Response Models   Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Intructions

</div>
</div>
<div class="layoutArea">
<div class="column"></div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Assignment Questions

Q1

We use Wage data set which is in the library ISLR2. The Wage data set contains the following variables.

<pre>##       year           age                     maritl           race
##  Min.   :2003   Min.   :18.00   1. Never Married: 648   1. White:2480
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
library(ISLR2) #head(Wage) summary(Wage)

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>##  1st Qu.:2004   1st Qu.:33.75   2. Married
##  Median :2006   Median :42.00   3. Widowed
##  Mean   :2006   Mean   :42.41   4. Divorced
##  3rd Qu.:2008   3rd Qu.:51.00   5. Separated    :  55
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>##
##
##
##
##  2. HS Grad
##  3. Some College   :650   3. East North Central:   0
##  4. College Grad   :685   4. West North Central:   0
##  5. Advanced Degree:426   5. South Atlantic    :   0
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
Max. :2009 1.&lt;HSGrad

</div>
<div class="column">
Max. :80.00

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>education                     region               jobclass
     :268   2. Middle Atlantic   :3000   1. Industrial :1544
     :971   1. New England       :   0   2. Information:1456
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>##
##
##
##  1. &lt;=Good
##  2. &gt;=Very Good:2142   2. No : 917   1st Qu.:4.447   1st Qu.: 85.38
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<ul>
<li>
<pre>## &nbsp;                                     Median :4.653
</pre>
</li>
<li>
<pre>## &nbsp;                                     Mean   :4.654
</pre>
</li>
<li>
<pre>## &nbsp;                                     3rd Qu.:4.857
</pre>
</li>
<li>
<pre>## &nbsp;                                     Max.   :5.763
##
</pre>
</li>
</ul>
</div>
<div class="column">
<pre>Median :104.92
Mean   :111.70
3rd Qu.:128.68
Max.   :318.34
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>6. East South Central:   0
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
(Other) :0 health_ins logwage wage

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>health
   : 858   1. Yes:2083   Min.   :3.000   Min.   : 20.09
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
In the first part of the assignment. We are interested in wage in relation to year, age and education. This is a paired plot.

<pre>pairs(data.frame(Wage$wage, Wage$year, Wage$age, Wage$education))
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>:2074   2. Black: 293
:  19   3. Asian: 190
: 204   4. Other:  37
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
Wage.wage

</div>
</div>
<div class="layoutArea">
<div class="column">
50 150 250

</div>
<div class="column">
20 40 60 80

</div>
</div>
<div class="layoutArea">
<div class="column">
2003 2005 2007 2009 1 2 3 4 5

</div>
</div>
<div class="layoutArea">
<div class="column">
Wage.year

</div>
</div>
<div class="layoutArea">
<div class="column">
Wage.age

</div>
</div>
<div class="layoutArea">
<div class="column">
It is known that year has approximately linear trend and the variable education is a categorical variable. We use the natural spline curve fitting for the trend of age. For this we use function ns() in the splines package and lm() function. We fit the following models

</div>
</div>
<div class="layoutArea">
<div class="column">
model1: model2: model3: model4: model5:

</div>
<div class="column">
waga ∼ year + ns(age, df = 1) + education, waga ∼ year + ns(age, df = 3) + education, waga ∼ year + ns(age, df = 5) + education, waga ∼ year + ns(age, df = 7) + education, waga ∼ year + ns(age, df = 9) + education.

</div>
</div>
<div class="layoutArea">
<div class="column">
(a) (10 marks) Fit the model and use anova() function to do the deviance test to compare the models. Choose the best model.

<pre>library(splines)
</pre>
<ol start="2">
<li>(b) &nbsp;(5 marks) Calculate AIC for each model fitted in (a). Choose the best model using the value of AIC.</li>
<li>(c) &nbsp;(10 marks) Split the data set (100%) into a training set (70%) and a test set (30%). Then fit model1–model5 on the training set, and calculate the test MSE for each model. Choose the best model.</li>
</ol>
set.seed(11)

(d) (10 marks) By combining the result from (a), (b) and (c), decide the best model. Refit the chosen

model using all of the Wage data set. Interpret the out of the summary() function. Q2

Here we will predict the number of applications received Apps using the other variables in the “College” data set.

The data set contains 777 observations on the following 18 variables.

</div>
</div>
<div class="layoutArea">
<div class="column">
Wage.education

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre># Private: A factor with levels No and Yes indicating private or public university
# Apps: Number of applications received
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
12345 2003 2007

</div>
</div>
<div class="layoutArea">
<div class="column">
20 40 60 80

</div>
<div class="column">
50 200

</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="layoutArea">
<div class="column">
<pre># Accept: Number of applications accepted
# Enroll: Number of new students enrolled
# Top10perc: Pct. new students from top 10% of H.S. class
# Top25perc: Pct. new students from top 25% of H.S. class
# F.Undergrad: Number of fulltime undergraduates
# P.Undergrad: Number of parttime undergraduates
# Outstate: Out-of-state tuition
# Room.Board: Room and board costs
# Books: Estimated book costs
# Personal: Estimated personal spending
# PhD: Pct. of faculty with Ph.D.'s
# Terminal: Pct. of faculty with terminal degree
# S.F.Ratio: Student/faculty ratio
# perc.alumni: Pct. alumni who donate
# Expend: Instructional expenditure per student
# Grad.Rate: Graduation rate
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>library(ISLR)
##
</pre>
<pre>## Attaching package: 'ISLR'
</pre>
<pre>## The following objects are masked from 'package:ISLR2':
##
##     Auto, Credit
</pre>
<pre>##  Private        Apps           Accept          Enroll
##  No :212   Min.   :   81   Min.   :   72   Min.   :  35
##  Yes:565   1st Qu.:  776   1st Qu.:  604   1st Qu.: 242   1st Qu.:15.00
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>data(College)
summary(College)
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<ul>
<li>
<pre>## &nbsp;           Median : 1558
</pre>
</li>
<li>## &nbsp;Mean : 3002</li>
<li>
<pre>## &nbsp;           3rd Qu.: 3624
</pre>
</li>
<li>
<pre>## &nbsp;           Max.   :48094
</pre>
</li>
<li>
<pre>## &nbsp;   Top25perc      F.Undergrad     P.Undergrad         Outstate
</pre>
</li>
<li>
<pre>## &nbsp; Min.   :  9.0   Min.   :  139   Min.   :    1.0   Min.   : 2340
##  1st Qu.: 41.0   1st Qu.:  992   1st Qu.:   95.0   1st Qu.: 7320
##  Median : 54.0   Median : 1707   Median :  353.0   Median : 9990
##  Mean   : 55.8   Mean   : 3700   Mean   :  855.3   Mean   :10441
##  3rd Qu.: 69.0   3rd Qu.: 4005   3rd Qu.:  967.0   3rd Qu.:12925
##  Max.   :100.0   Max.   :31643   Max.   :21836.0   Max.   :21700
##    Room.Board       Books           Personal         PhD
</pre>
<pre>##  Min.   :1780   Min.   :  96.0   Min.   : 250   Min.   :  8.00
##  1st Qu.:3597   1st Qu.: 470.0   1st Qu.: 850   1st Qu.: 62.00
##  Median :4200   Median : 500.0   Median :1200   Median : 75.00
##  Mean   :4358   Mean   : 549.4   Mean   :1341   Mean   : 72.66
##  3rd Qu.:5050   3rd Qu.: 600.0   3rd Qu.:1700   3rd Qu.: 85.00
##  Max.   :8124   Max.   :2340.0   Max.   :6800   Max.   :103.00
##     Terminal       S.F.Ratio      perc.alumni        Expend
</pre>
<pre>##  Min.   : 24.0   Min.   : 2.50   Min.   : 0.00   Min.   : 3186
##  1st Qu.: 71.0   1st Qu.:11.50   1st Qu.:13.00   1st Qu.: 6751
##  Median : 82.0   Median :13.60   Median :21.00   Median : 8377
##  Mean   : 79.7   Mean   :14.09   Mean   :22.74   Mean   : 9660
</pre>
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>Median : 1110
Mean   : 2019
3rd Qu.: 2424
Max.   :26330
</pre>
</div>
<div class="column">
<pre>Median : 434
Mean   : 780
3rd Qu.: 902
Max.   :6392
</pre>
</div>
<div class="column">
<pre>Median :23.00
Mean   :27.56
3rd Qu.:35.00
Max.   :96.00
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>  Top10perc
Min.   : 1.00
</pre>
</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
<pre>##  3rd Qu.: 92.0   3rd Qu.:16.50   3rd Qu.:31.00   3rd Qu.:10830
##  Max.   :100.0   Max.   :39.80   Max.   :64.00   Max.   :56233
##    Grad.Rate
##  Min.   : 10.00
</pre>
<pre>##  1st Qu.: 53.00
##  Median : 65.00
##  Mean   : 65.46
##  3rd Qu.: 78.00
##  Max.   :118.00
</pre>
(a) (5 marks) (Create trainig set and test set) Split the data set (100%) into a training set (70%) and a test set (30%).

set.seed(11)

(b) (10 marks) (LASSO) Fit a lasso model on the training set, with λ chosen by cross-validation with the

1 se rule . Report the test error obtained, along with the of non-zero coefficient estimates. library(glmnet)

<pre>## Loading required package: Matrix
## Loaded glmnet 4.1-3
</pre>
<pre>grid &lt;- 10 ˆ seq(4, -2, length = 100)
</pre>
• Test MSE

• Non-zero coefficient estimates

(c) (10 marks) Do the best subset selection with BIC and choose the best model.

<pre>library(leaps)
</pre>
(d) (10 marks) Use all of the College data set, refit the models chosen by LASSO in (b) and best subset selection in (c). Print output of the function summary() for these models. Then compute ‘AIC’ and

‘BIC’. Between these 2 models, which model is the better model. Give reasons why.

[Total: 70 marks]

</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
