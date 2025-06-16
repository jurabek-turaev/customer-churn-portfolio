## Ushbu amaliyotda biz, mijozlar noroziligi(customer churn)ni aniqlaymiz

Biznesda eng ko'p uchraydigan muammolardan biri. Mijozning kayfiyatini aniqlash.

Agar biznes egasi mijoz qaytmasligini, maxsulot yoki xizmatdan qayta foydanalmasligini oldindan bashorat qila olsa, mijozni ushlab qolish uchun, uning fikrini o'zgartirish uchun harakat qilishi mumkin.

Ushbu amaliyotda biz online do'kon xaridorlari ma'lumotlarini tahlil qilish orqali mijozning qolish-qolmasligini bashorat qilamiz.

Amaliyotda asosan python kutubxonalaridan foydalanilgan holda tahlil o'tkazilgan. Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn asosiy kutubxonlar. 

Datasetning bir nechta vizual ko'rinishlari:
Asosiy sonli ustunlar:
![image](https://github.com/user-attachments/assets/fd838ac2-322b-4fc2-8a59-665d9336076c)

Asosiy matnli ustunlar:
![image](https://github.com/user-attachments/assets/7cef74a7-85cc-4ad2-b613-947d3fd9621e)


Amaliyotda asosiy 4ta model qurib, ushbu `https://github.com/anvarnarz/praktikum_datasets/blob/main/E-Commerce-Dataset.xlsx?raw=true` datasetda train qilindi. Bular: LogisticRegression, SupportVector Machine, RandomForestClassifier, DecisionTreeClassifier va XGBClassifier
Model natijalari quyidagicha:
LogisticRegression:
              precision    recall  f1-score   support

           0       0.89      0.98      0.93       941
           1       0.76      0.37      0.50       185

    accuracy                           0.88      1126
   macro avg       0.83      0.67      0.71      1126
weighted avg       0.87      0.88      0.86      1126

Model aniqligi: 
 0.8774422735346359


Support Vector Machine:
              precision    recall  f1-score   support

           0       0.87      0.98      0.92       941
           1       0.74      0.27      0.40       185

    accuracy                           0.86      1126
   macro avg       0.80      0.63      0.66      1126
weighted avg       0.85      0.86      0.84      1126


Decision Tree:
              precision    recall  f1-score   support

           0       0.97      0.97      0.97       941
           1       0.86      0.85      0.85       185

    accuracy                           0.95      1126
   macro avg       0.91      0.91      0.91      1126
weighted avg       0.95      0.95      0.95      1126

Model aniqligi: 0.9520426287744227


Random Forest:
              precision    recall  f1-score   support

           0       0.97      0.97      0.97       941
           1       0.86      0.85      0.85       185

    accuracy                           0.95      1126
   macro avg       0.91      0.91      0.91      1126
weighted avg       0.95      0.95      0.95      1126

Accuracy score: 0.9520426287744227


XGBoost:
              precision    recall  f1-score   support

           0       0.95      0.99      0.97       941
           1       0.93      0.72      0.81       185

    accuracy                           0.94      1126
   macro avg       0.94      0.85      0.89      1126
weighted avg       0.94      0.94      0.94      1126

Accracy score: 0.9449378330373002




### Bulardan eng yuqori natijaga erishilgani bu - DecisionTree modeli bo'ldi. Uning natijasini quyidagi vizual ko'rinishda ko'rishingiz mumkin:
              precision    recall  f1-score   support

           0       0.98      0.98      0.98       941
           1       0.88      0.88      0.88       185

    accuracy                           0.96      1126
   macro avg       0.93      0.93      0.93      1126
weighted avg       0.96      0.96      0.96      1126

Model aniqligi: 0.9591474245115453

![image](https://github.com/user-attachments/assets/e12d6158-689a-499e-a028-42b1348b7c97)
ROC Curve:
![image](https://github.com/user-attachments/assets/528d44df-79b8-4f65-9dba-2d99137596ac)

Tree:
![image](https://github.com/user-attachments/assets/c0266284-9d98-4242-9d1a-23004e9961a8)



