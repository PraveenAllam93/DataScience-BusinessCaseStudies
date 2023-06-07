## Root Cause Analysis

**What is Root Cause Analysis?**
--
* A root cause is the underlying cause of the core issue, analysing this issue in a systematic process is called root cause analysis
* It is defined as a collective term that describes a wide range of approaches, tools, and techniques used to uncover causes of problems
* It involves breaking down the problem into smaller parts, examining each part in detail, and identifying the root causes that are contributing to the problem

**Goals of Root Cause Analysis:**
--
* Identify the root cause of the issue
* Understand and fix the issue, compendate or learn from any underlying issue within the root cause
* Apply the things we learned from analysis to ensure success or prevent future issues


**How to solve this kind of problems**
--
We use CRIEd (Clarify, Rule out, Internal data, External data) framework to do RCA

*Clarify*
--
* Understanding the problem in depth
* Calrification of terms and parameters
* Creating an outline to the approach

*Rule out*
--
* Ruling out the issues that seems that are out of scope 
* Exploring the possibilities and listing out some high level causes
eg: internet breakage, negative campaign, server break down...
  
*Internal Data*
--
   For Internal Data (Factors), we use another framework called 
   1. TROPiCS (Time, Region, Other features, Platform, Cannabalisation, Segementation) and 
   2. if the product on which we're performing is a marketplace we do prefer Customer User Journey (CUJ) too

* Customer User Journey:
   * A session is the period of time that passes from the moment that an application is launched until it is closed
   * The step at which the user closes the application is a drop off for that step
   * If a user leaves the home page without taking any further action, it is known as a bounce rate
   
   In the CUJ we check the percentage of drop offs at every step, is it similar to the hisotical data or not. If we observe any difference we perform TROPiCS framework in that particular stage where we saw the difference
   
 
  <img width="396" alt="Screenshot 2023-06-07 at 15 45 18" src="https://github.com/PraveenAllam93/DataScience-BusinessCaseStudies/assets/33192828/b295cacb-68af-47ba-922f-449577526233">
  
  These are the stages in most of the marketplaces applications
  
* TROPiCS:
   * Time, we check any differneces with respect any timeframe of the day
   * Region, we check if the issue is restricted to any particular region or place or whole world
   * Other realted features, we check if the other related features with this issues are also getting effected or not
   * Platform, if the issue is with web app or iOS or Android
   * Cannibalization, checking if any of our own product is the reason for this issue
   * Segmentation, grouping the data checking the issue over differnet groups like age, gender, marital status, exsitsing users vs new users, power users vs casual users....


*External Data*
--
* Chekcing if the competitor is doing good
* It could also be due to seasonality or a major temporary event
* Good PR
   
   
*After all these steps we can get to a solution to solve the issue, the RCA should be done step by step which is a slow process sometimes but helps to solve the core issue*   

  
  
