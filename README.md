# تشخیص ارقام دست‌نویس: مقایسه الگوریتم‌های طبقه‌بندی یادگیری ماشین

<p align="center">
  <img src="https://raw.githubusercontent.com/scikit-learn/scikit-learn/main/doc/logos/scikit-learn-logo.png" width="200" alt="scikit-learn logo">
</p>

## توضیحات پروژه
این پروژه به بررسی و مقایسه عملکرد چهار الگوریتم طبقه‌بندی مختلف یادگیری ماشین در تشخیص ارقام دست‌نویس می‌پردازد. از مجموعه داده MNIST استفاده شده که شامل تصاویر ۸×۸ پیکسلی از ارقام دست‌نویس است.

### الگوریتم‌های مقایسه شده
- **جنگل تصادفی (Random Forest)**
- **ماشین بردار پشتیبان (SVM)**
- **شبکه عصبی مصنوعی (ANN)**
- **نزدیک‌ترین همسایه (KNN)**

### نتایج
الگوریتم‌های مورد بررسی دقت بالایی در تشخیص ارقام دست‌نویس نشان دادند:
- SVM: دقت ۹۹.۴۴٪
- KNN: دقت ۹۸.۸۹٪
- ANN: دقت ۹۸.۰۶٪
- Random Forest: دقت ۹۸.۳۳٪

## نحوه استفاده
برای اجرای این پروژه، ابتدا کتابخانه‌های مورد نیاز را نصب کنید:
```bash
pip install -r requirements.txt
```

سپس می‌توانید فایل نوت‌بوک Jupyter را اجرا کنید:
```bash
jupyter notebook project1.ipynb
```

---

# Handwritten Digit Recognition: Comparison of Machine Learning Classification Algorithms

<p align="center">
  <img src="https://raw.githubusercontent.com/scikit-learn/scikit-learn/main/doc/logos/scikit-learn-logo.png" width="200" alt="scikit-learn logo">
</p>

## Project Description
This project examines and compares the performance of four different machine learning classification algorithms in recognizing handwritten digits. The MNIST dataset is used, which contains 8×8 pixel images of handwritten digits.

### Compared Algorithms
- **Random Forest**
- **Support Vector Machine (SVM)**
- **Artificial Neural Network (ANN)**
- **K-Nearest Neighbors (KNN)**

### Results
The evaluated algorithms showed high accuracy in recognizing handwritten digits:
- SVM: 99.44% accuracy
- KNN: 98.89% accuracy
- ANN: 98.06% accuracy
- Random Forest: 98.33% accuracy

## How to Use
To run this project, first install the required libraries:
```bash
pip install -r requirements.txt
```

Then you can run the Jupyter notebook:
```bash
jupyter notebook project1.ipynb
```

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. 