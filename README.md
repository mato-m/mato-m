### Introduction 👋
Hello, my name is Mato.<br/>
I'm a web & mobile app developer, as well as an AI enthusiast.<br/>
I'm constantly working on gaining and improving my skills, as well as creating new and improving my existing projects.
### Expertise 👨‍💻
| **Languages** | **Frontend**    | **Backend**     | **Machine learning**         | **Other Tools**           |
|:-------------:|:---------------:|:---------------:|:--------------:|:---------------------------:|
| JavaScript    | React           | Node.js         | Numpy          | Figma     |
| TypeScript    | React Native    | Express.js     | Pandas         | Illustrator|
| Python        | Angular         | Flask           | Scikit-learn   | Linux CLI                      |
| PHP           | Next.js         | JWT             | Tensorflow     | Docker                         |
| Java          | CSS frameworks       | SQL databases                | Keras          | npm                            |
| C#            |     Wordpress            | MongoDB                  | PyTorch        |  Version control                           |
### Projects
#### Web & mobile apps 🌎
| **Project name** | **Tools used**    | **Description**     | **Demo** | **Repo** |
|:-------------:|:---------------:|:---------------:|:-------------:|:-------------:|
| Movie info site    | React<br/> Express.js<br/> Postgres           | This web app enables its users to easily find information about movies and actors. The movies can be viewed by genre, service they are available on and the languages they are available in. Users can also create their own lists with different movies, which can be either public or private. Users can keep track of their watched movies. Users can also rate movies and browse them by their rating.         | Coming soon           | [movie-frontend](https://github.com/mato-m/movie-frontend)<br/>[movie-backend](https://github.com/mato-m/movie-backend)         |
| News portal    | React<br/> Express.js<br/> Postgres    | This is a web app that enables users to read and browse news articles. Users can find the articles by their tags, categories and subcategories. Users can comment on articles. The publishers can easily write and edit their articles using Markdown editor.     | Coming soon       | [news-frontend](https://github.com/mato-m/news-frontend)<br/>[news-backend](https://github.com/mato-m/news-backend)         |
| Expense tracker        | React Native         | This is a simple and lightweight Android application that enables its users to easily keep track of their expenses and incomes. The users can track their expenses or incomes on a daily, monthly or a yearly basis, as well as across different categories. The data is stored locally and the application works offline.           |        [Play Store](https://play.google.com/store/apps/details?id=com.mato.xo.troskovi)       | [troskovi-app](https://github.com/mato-m/troskovi-app)         |
| Rent a car website       | React         | A simple website with a modern and responsive UI design made in React to showcase cars for a rent-a-car company. By selecting a car, the user can get detailed information about it, as well as its prices.          |        [Demo](https://rentmne.netlify.app/)       | [rent-car-react](https://github.com/mato-m/rent-car-react)         |
| Crypto tracker       | React         | A simple homepage for a website that enables users to track latest changes in cryptocurrency prices. The page has a modern and responsive UI design, as well as an example of a chart that showcases the latest cryptocurrency prices.           |        [Demo](https://crypto-track-react-app.netlify.app/)       | [crypto-frontend](https://github.com/mato-m/crypto-frontend)         |
#### AI 🧠
##### Deep learning
| **Project name** | **Model**    | **Description**     | **Dataset** | **Repo** |
|:-------------:|:---------------:|:---------------:|:-------------:|:-------------:|
| Vehicle counting    | YOLO           | This project utilizes a pretrained YOLO model that recognizes vehicles. It is used in order to count the number of cars that pass the specified line on the video.         | [Used video](https://www.youtube.com/watch?v=MNn9qKG2UFI)           | [yolo-vehicle-counting](https://github.com/mato-m/yolo-vehicle-counting)        |
| Grapevine disease classification    | ResNet50    |  This project uses ResNet50, a pretrained convolutional neural network, in order to classify images of grapevines based on its condition or disease. The model achieved the accuracy higher than 99% on both the training and the test dataset.     | [Grapevine disease dataset](https://www.kaggle.com/datasets/rm1000/grape-disease-dataset-original)       | [resnet-grape](https://github.com/mato-m/resnet-grape)   |
##### Classification
| **Project name** | **Model**    | **Description**     | **Dataset** | **Repo** |
|:-------------:|:---------------:|:---------------:|:-------------:|:-------------:|
| Diabetes prediction    | K-nearest neighbors           | This model uses k-nearest neighbors algorithm in order to predict if a patient has diabetes based on glucose level, body mass index and age. The model achieved only 64% F1 score, which is not very accurate.          | [Diabetes Dataset](https://www.kaggle.com/datasets/mathchi/diabetes-data-set)           | [knn-diabetes](https://github.com/mato-m/knn-diabetes)         |
| Gender classification    | Stochastic gradient descent           | This model uses Stochastic gradient descent algorithm to predict the gender of a person based on values of facial features. The model was able to predict the gender accurately in around 96% of test cases, which means that the model is very accurate. The model predicted the gender based on nose width, nose length, distance from nose to lip and lip size.          | [Gender classification dataset](https://www.kaggle.com/datasets/elakiricoder/gender-classification-dataset)           | [gender-classification](https://github.com/mato-m/gender-classification)         |
| Wine clustering    | Random forest    | This model uses random forest algorithm in order to predict the quality of wine based on its other parameters such as acidity and sulfur dioxide level. The model achieved 81.25% F1 score, so it can be considered as highly accurate.      | [Red Wine Quality](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009)       | [rf-wine](https://github.com/mato-m/rf-wine)   |
| Bank note authentication    | Support Vector Machine<br/>Principal component analysis    | This model uses Support Vector Machine algorithm in order to determine if a bank note is authentic or not. The model uses data that describe skewness, variance, curtosis and entropy in order to make the prediction. The model achieved a very high accuracy of 99.5%.     | [Bank Note Authentication](https://www.kaggle.com/datasets/ritesaluja/bank-note-authentication-uci-data)       | [svm-banknote](https://github.com/mato-m/svm-banknote)   |
##### Regression
| **Project name** | **Model**    | **Description**     | **Dataset** | **Repo** |
|:-------------:|:---------------:|:---------------:|:-------------:|:-------------:|
| Car price prediction    | Linear regression<br/> Random forest regression           | This project compares two regression models. Its main goal is to predict the car price based on its model, year and mileage. Linear regression achieved the 6864 root mean squared error, while random forest achieved  1426 RMSE, which is a significantly better result.        | [US Cars Dataset](https://www.kaggle.com/datasets/doaaalsenani/usa-cers-dataset)           | [regression-cars](https://github.com/mato-m/regression-cars)         |
##### Clustering
| **Project name** | **Model**    | **Description**     | **Dataset** | **Repo** |
|:-------------:|:---------------:|:---------------:|:-------------:|:-------------:|
| Wine clustering    | K-means<br/>Principal component analysis    | This model uses K-means in order to cluster wine based on different parameters such as alcohol levels, magnesium levels and color intensity. Using both elbow method and silhouette score it was determined that the optimal number of clusters is 6. Principal component analysis was used in order to visually represent the result on a 2D chart.     | [Wine dataset](https://www.kaggle.com/datasets/harrywang/wine-dataset-for-clustering)       | [kmeans-wine](https://github.com/mato-m/kmeans-wine)   |

### Career 💼


#### DigitalSmart
* 📅 Duration: December 2022 - October 2023
* 📍 Location: Podgorica, Montenegro
* 💻 Position: Web developer
* 📝 Summary:
    * 📝 Part of FishEUTrust, project funded under the Horizon Europe programme
    * 📝 Developed a scalable, high-performing web application
    * 📝 Ensured fast and secure connection to REST API routes
    * 📝 Enabled geographic data management, visualization and processing using OpenStreetMap
    * 📝 Enabled sensor data management, visualization and processing using ApexCharts
    * 📝 Implemented secure processes for user authentication and authorization
#### Walmart
* 📅 Duration: June 2022 - September 2023
* 📍 Location: Myrtle Beach, SC, United States
* 💻 Position: Associate
* 📝 Summary:
    * 📝 Responsible for inventory management in one of South Carolina's largest Supercenters
    * 📝 Provided over a 1000 customers with excellent customer service
    * 📝 Participated in many successful direct sales
#### Self-employed
  * 📅 Duration: February 2021 - June 2022
  * 📝 Summary:
    * 📝 Developed over 15 high-performing web & mobile apps
    * 📝 Developed UI designs that are visually appealing, responsive, and user-friendly
    * 📝 Oversaw search engine and social media marketing, which resulted in a notable increase in traffic
    * 📝 Implemented strategies to ensure web apps attain high on-page SEO scores
    * 📝 Provided customers with assistance and guidance
### Education 🎓
#### Master of AI
* 📅 Duration: 2022 - 2024
* 🏫 Studied at: University of Donja Gorica
* 📄 Thesis: Computer vision in viticulture


#### Bachelor of IT
* 📅 Duration: 2019 - 2022
* 🏫 Studied at: University of Donja Gorica
* 📄 Thesis: Machine learning and cryptocurrency price prediction
* 🏆 Awards:
  * 🏆 Best student of the class of 2019 (9.64 GPA)
  * 🏆 Scholarship for the best students from Cetinje
  * 🏆 Scholarship for the best students from Montenegro
