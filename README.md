# Baitest-Building-Evaluation-System
<div align="center">
<h1>
<b>
Baitest --A Building Evaluation System
</b>
</h1>
</div>

> [Demo video](https://youtu.be/U8PfB93wCx0)

> [Meeting Note](https://docs.google.com/document/d/1PPSkh5ZNaXh1GiIWawdBqzbC4-HKz2NTu9-rDip23mg/edit )

> [Survey Link](https://forms.gle/e5ZKm39eXKEoAYRi9)

## :fire: Introduction
The goal of the BaiTest platform is to understand and deploy challenges related to AI-based building load forecasting models.
<br>
<br>
BaiTest can be used by building AI developers to compare
and select appropriate ML models. Our preliminary experiments show that a model with
high maintainability or reliability can show 3%-10% more energy saving against a model
with the highest accuracy. BaiTest can allow effective use of the large number of ML
models and accelerate ML model deployment; this can lead to tens of millions of saving.

## :heart: Analysis of ISO standard into our scenario
  Our goal is again to define what tests we shall apply to an ML model. We plan to design the evaluation methodology following the ISO/IEC 25010 [4, 5], a software quality standard. ISO25010 describes 13 characteristics consists of product quality and quality in use, for example, availability, reusability and efficiency, etc. In BaiTest, we plan to leverage a subset of characteristics as shown in the following table.
  We translate the ISO standard into the context of buildings, and we plan to test both (a) a building load forecasting ML model and (b) its associated energy control. We list the corresponding evaluation checklists in terms of buildings as shown in the right table.

<div align="center">
  <img src="images/Iso.png">
</div>

## :star: Front-end design
* User-guider design
  
<div align="center">
  <img src="images/User_guide.png">
</div>

* Role selection and building selection/upload design
  
<div align="center">
  <img src="images/Role_building_selection.png">
</div>

* Building data analysis design
  
<div align="center">
  <img src="images/Analyse.png">
</div>

* Building evaluation result display design
  
<div align="center">
  <img src="images/Result1.png">
  <img src="images/Result2.png">
</div>

## :eyes: Survey result
We designed a questionnaire to study (i) In practice, does building load forcasting model should be carefully selected among different buildings?(ii) When using the building load forcasting model, what metric of the model do they care about? To gain those information we deisnged four part question, i.e., ueser related, AI evaluation related, data related and model management related.
<br>
<br>
The questionnaires include single choice, multiple choice and fill-in-the-blank questions. So we selected one question result in each type to present. From the results, we can conclude that (i) 77% of the interviewees' workes or studies are related to building load forecasting, (ii) 87.5% interviewees think  different buildings are required different load forcasting models. (iii) Most interviewees think the missing rate and the main pattern are the most important when they collect data from target building.
<div align="center">
  <img src="images/Survey_result.png">
</div>

