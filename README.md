<div align="center">
 <a href="https://github.com/aaronDev28/Bangalore_House_Price_Prediction_oneAPI" >   
  <img src="https://github.com/joelbkoshy/Assets/blob/main/pngwing.com.png" width="80" height="90">
  </div>
  <h1 align="center">BANGALORE HOUSE PRICE PREDICTION </h1>

  <p align="center">
      Welcome to our project!
    <br />
    <br />
    <a href="https://www.youtube.com/watch?v=l9oMgSgGNek">View Demo</a>
  </p>
</div>

# Inspiration Behind The Project <img src= "https://user-images.githubusercontent.com/72274851/218500470-ec078b99-0a50-4b06-a2df-c09e47ecc187.png" width="50" height="50"> 

<ul>
  <li><b>Project objective:</b> To develop a machine learning-based model to predict home prices accurately for potential homebuyers in Bangalore.</li>
  <li><b>Factors considered:</b> The model takes into account various factors that influence property prices, such as location, proximity to essential facilities, market trends, and more.</li>
  <li><b>Project motivation:</b> To empower potential homebuyers with accurate price predictions and help them make informed decisions, avoid overpaying, and negotiate better deals. The project can also benefit real estate agents and property developers in estimating prices for their properties and making informed decisions.</li>
  <li><b>Expected outcomes:</b> The project aims to provide a reliable solution to an essential problem in the real estate industry and be useful to anyone interested in buying or selling properties in Bangalore.</li>
</ul>

# What It Does <img src= "https://user-images.githubusercontent.com/72274851/218503394-b52dfcc9-0620-4f44-94f5-46a09a5cc970.png" width="50" height="50">

<div align="center">
 <img src="https://github.com/joelbkoshy/Assets/blob/main/projectgif.gif" type="gif" alt="png" width="750">
 </div>

<h2>Project Description</h2>
<p>Bengaluru House Prediction is an advanced machine learning model that predicts the estimated home price based on various features such as square feet, bedroom, bathroom, location, and more. It follows a robust data science process, including data loading and cleaning, outlier detection and removal, feature engineering, dimensionality reduction, and hyperparameter tuning using GridSearchCV and k-fold cross-validation. The project is built on a Python Flask server that consumes the trained machine learning model and exposes HTTP endpoints for various requests. Additionally, it uses a pickle file to store the trained model.</p>
<h2>User Interface</h2>
<p>The project features a sleek and intuitive user interface using HTML, CSS, and JavaScript. It allows users to input the necessary features and receive an instant price prediction. </p>
<h2>Benefits</h2>
<p>Bengaluru House Prediction is a powerful tool that can benefit potential homebuyers, real estate agents, and property developers. It empowers users with the right information to make informed decisions, negotiate better deals, and avoid overpaying. The project also demonstrates the power of data science in solving real-world problems and provides a robust framework for developing similar machine learning applications.</p>

### Built With 

This section should list any major frameworks/libraries used to bootstrap your project. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.

* [![oneapi][oneapi]][oneapi-url]
*  [![Scikit-learn ][Scikit-learn]][Scikit-learn]
* [![onedal][onedal]][onedal-url]
* [![Flask][Flask]][Flask-url]
* [![python][python]][python-url]
* [![jupyter][jupyter]][jupyter-url]

## Intel oneAPI <img src="https://github.com/joelbkoshy/Assets/blob/main/oneapi2.png" alt="png" width="30">

Intel oneAPI is a comprehensive suite of software development tools designed to simplify the development of high-performance applications across a variety of architectures, including CPUs, GPUs, FPGAs, and other accelerators. One of the main benefits of oneAPI is that it enables developers to take advantage of the full power of modern hardware, including the latest CPUs and GPUs, without having to write separate code for each platform. This can help save time and reduce development costs, as well as improve the overall performance of the application. Some common uses of oneAPI include developing machine learning models, accelerating data analytics workloads, and optimizing scientific simulations.



### Use of oneDAL

In our Bengaluru House Price Prediction project, we used the oneDAL library of Intel oneAPI to optimize and accelerate our machine learning models. By using the oneDAL library, we were able to take advantage of Intel's industry-leading optimization and parallelization capabilities to improve the efficiency, accuracy, and performance of our models.

To use oneDAL in our project, we applied the sklearnex patch to our machine learning models. This was done using the code:

```
from sklearnex import patch_sklearn
patch_sklearn()
```

Some few examples in the project:<br>
<img src="https://github.com/joelbkoshy/Assets/blob/main/intel1.png" alt="png" width="600">
<img src="https://github.com/joelbkoshy/Assets/blob/main/intel2.png" alt="png"  width="600">

This allowed us to seamlessly integrate oneDAL into our existing codebase and take advantage of its powerful capabilities without having to rewrite our entire code. With oneDAL, we were able to accelerate the training of our models and improve their accuracy, allowing us to make more accurate predictions about the prices of houses in Bengaluru based on various features such as square feet, bedrooms, bathrooms, and location.

Overall, the use of oneDAL in our project was crucial to achieving the level of accuracy, efficiency, and optimization necessary for accurate house price predictions. By leveraging the power of Intel's oneAPI platform, we were able to take our machine learning models to the next level and produce results that exceeded our expectations.


# How We built it <img src= "https://user-images.githubusercontent.com/72274851/218502434-f6e66043-0db0-4f85-b7f4-f33b2d33df1f.png" alt="png" width="50">

### ✅ First We Imported libraries

### ✅Understand the [Data](https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data)

### ✅Test Different Models and find the best model out of it

### ✅Train the model using Intel oneDAL to get better results and faster computation(Intel oneAPI Data Analytics Library (oneDAL))
![intel](https://github.com/joelbkoshy/read/blob/main/Bar_chart.png)
![intel](https://github.com/joelbkoshy/read/blob/main/model.png)



### ✅Save the model

### User Interface
![intel](https://github.com/joelbkoshy/read/blob/main/ui.png)

# What we learned <img src= "https://user-images.githubusercontent.com/72274851/218499685-e8d445fc-e35e-4ab5-abc1-c32462592603.png" alt="png" width="50">


![image](https://user-images.githubusercontent.com/72274851/220130227-3c48e87b-3e68-4f1c-b0e4-8e3ad9a4805a.png)

- Real estate industry is complex and influenced by various factors, such as location, amenities, and market trends, which can be leveraged using machine learning to predict accurate prices.
- A robust data science process, including data loading and cleaning, outlier detection and removal, feature engineering, dimensionality reduction, and hyperparameter tuning using GridSearchCV and k-fold cross-validation, is necessary to build an accurate and efficient machine learning model.
- A user-friendly interface using HTML, CSS, and JavaScript can help users interact with the machine learning model and understand the factors that influence the predicted price.
- Python, Intel One API, Intel oneDAL, Scikit-learn, Pandas, Numpy, Flask, Matplotlib, GridSearchCV, K-fold cross-validation, and Pickle are powerful tools and libraries used in developing machine learning models and web applications.
The project demonstrates the power of data science in solving real-world problems and provides a robust framework for developing similar machine-learning applications.

These are just a few examples of the knowledge and skills that i likely gained while building this project. 
Overall, building a price prediction application is a challenging and rewarding experience that requires a combination of technical expertise and real estate knowledge.



[python]: https://img.shields.io/badge/Python-3470a3?&logoColor=white
[python-url]: https://www.python.org/
[jupyter]: https://img.shields.io/badge/Jupyter%20Notebook-da5b0b?&logoColor=white
[jupyter-url]: https://jupyter.org/
[Scikit-learn]: https://img.shields.io/badge/Scikit-learn-20232A?&logoColor=61DAFB
[Scikit-learn-url]: https://www.intel.com/content/www/us/en/docs/oneapi/programming-guide/2023-0/intel-oneapi-data-analytics-library-onedal.html
[Flask]: https://img.shields.io/badge/Flask-90E0EF?&logoColor=white
[Flask-url]: https://www.intel.com/content/www/us/en/docs/oneapi/programming-guide/2023-0/intel-oneapi-data-analytics-library-onedal.html
[oneapi]: https://img.shields.io/badge/Intel%20oneAPI-20232A?&logoColor=61DAFB
[oneapi-url]: https://www.intel.com/content/www/us/en/docs/oneapi/programming-guide/2023-0/intel-oneapi-data-analytics-library-onedal.html
[onedal]: https://img.shields.io/badge/oneDAL-20232A?&logoColor=61DAFB
[onedal-url]: https://www.intel.com/content/www/us/en/developer/tools/oneapi/onedal.html


