
# سلفني: تحليل بيانات القروض الشخصية  
**(Sellefni: Personal Loan Analysis)**

## نظرة عامة (Overview)
هذا المشروع يهدف إلى تحليل البيانات المتعلقة بالقروض الشخصية وبناء نموذج تنبؤي يمكنه تقدير ما إذا كان الشخص مؤهلاً للحصول على قرض أم لا.  
(This project aims to analyze personal loan data and build a predictive model to estimate whether a person qualifies for a loan or not.)  

# الملف على كاجل:
https://www.kaggle.com/code/nacernacer/sellefni-personal-loan-analysis-arabic


## المميزات (Features)
- **تحليل البيانات الاستكشافية (Exploratory Data Analysis):**  
  - توزيع المتغيرات وتحليل العلاقات بينها.  
  (Analyzing variable distributions and their relationships.)  
- **بناء نموذج تعلم الآلة (Machine Learning Model):**  
  - تدريب نموذج الغابة العشوائية (Random Forest) للتنبؤ بنتيجة القرض.  
  (Training a Random Forest model to predict loan outcomes.)  
- **النتائج المرئية (Visual Results):**  
  - عرض التوصيات باستخدام الرسوم البيانية بلونين:  
    - الأخضر: مؤهل للحصول على القرض.  
    - الأحمر: غير مؤهل للحصول على القرض.  
  (Visualizing results with green for loan approval and red for rejection.)  

## الاستخدام (Usage)
1. استيراد البيانات وتدريب النموذج.  
2. تقديم بيانات شخص جديد واستخدام النموذج للتنبؤ بنتيجة القرض.  
(Import the data, train the model, and predict loan outcomes for new individuals.)  

## المتطلبات (Requirements)
- Python 3.x  
- المكتبات المطلوبة:  
  - pandas  
  - numpy  
  - matplotlib  
  - seaborn  
  - scikit-learn  
  - arabic-reshaper  
  - bidi  

## كيف تعمل (How It Works)
1. تجهيز البيانات: تنظيف البيانات وتحويل المتغيرات الفئوية.  
2. بناء النموذج: تدريب النموذج باستخدام بيانات التدريب.  
3. التنبؤ بالنتائج: إدخال بيانات جديدة والحصول على التوصية.  

## المؤلف (Author)
Developed by **ABDENNACER Elbasri**  
- **Twitter**: [@abdennacerelb](https://twitter.com/abdennacerelb)  
- **LinkedIn**: [@elbasri](https://linkedin.com/in/elbasri)  
