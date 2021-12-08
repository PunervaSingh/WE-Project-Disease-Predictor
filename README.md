# MediSphere - Disease Diagnosis
### MediSphere is a web application that diagnose disease using machine learning model based on the symptoms that the user enters.
[Website Link](https://we-project-disease-predictor.herokuapp.com/)
* We diagnose the disease if the patient is not in danger and the user simply wants to know what disease he or she might have.
* The dataset consisting of at least 100 symptoms, is used to train the model to diagnose various diseases.
* The web application provides latest health related news from all over the world.
* It also provide information of nearby healthcare center to the user along with emergency helpline numbers.
* The website provides information such as causes, symptoms and prevention related to common diseases. 
* It includes yoga instruction for preventing some of the most common ailments.

### 📌 Table of Contents
* [Toolchain](#toolchain)
* [Features](#features)
* [Application Overview](#overview)
* [Learnings](#learning)
* [Challenges faced](#challenges)
* [Future Scope/ What's next?](#scope)
* [Resources](#resources)
* [Setup](#setup)
* [Authors](#authors)
* [Bug Reporting](#bug)
* [Feature Requests](#feature-request)


<a id="toolchain"></a>
## 💻 Toolchain

<img alt="HTML" src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white"/><img alt="CSS" src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white"/><img alt="Javascript" src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"/><img alt="Bootstrap" src="https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white"/><img alt="Flask" src="https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white"/><img alt="Pandas" src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white" /><img alt="Numpy" src="https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white" /><img alt="Scikit-learn" src="https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white" /><img alt="SQLite" src="https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white" /><img alt="Visual Studio Code" src="https://img.shields.io/badge/VisualStudioCode-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white"/><img alt="Git" src="https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white"/>

***Frontend*** : HTML, CSS, JS, Bootstrap

***Backend*** : Flask, Jinja

***Dtabase*** : SQLite

***Libraries*** : Pandas, Numpy, Scikit-learn, GSAP

***API*** : NewsApi, MapBox, Kommunicate

***Other*** : Dialogflow, Git - Version Control, Visual Studio Code


<a id="features"></a>
## 🚀 Features
<!-- - The user is required to register with the system, in order to access the features of the web application. -->
<!-- - The disease is predicted using the algorithm(Decision Tree Classifier) and the user has to enter the symptoms from the given drop-down menu.
- The web application suggests treatments through a chat-bot(Medibot) that is meant to deal with the prognosis and some relevant information about the same.
- Provides the information about the nearby healthcare centers. -->
- Disease Diagnosis
- Up-to-date health-related news
- Nearby medical facilities
- Emergency helpline numbers
- Information related to common diseases
- Health Trivia
- Yoga Guide
- Chat-Bot
- [Add more features](#feature-request)...

<a id="overview"></a>
## 📖 Application Overview
### Home Page
![Website Image](flaskblog/static/img/main.png?raw=true "Title")
### About Page 
![Website Image](flaskblog/static/img/about.png?raw=true "Title")
### Manoeuvre Page 
![Website Image](flaskblog/static/img/prevention.png?raw=true "Title")
### Bulletin Page 
![Website Image](flaskblog/static/img/news.png?raw=true "Title")
<!-- ### Register Page 
![Website Image](flaskblog/static/img/register.png?raw=true "Title")
### Login Page
![Website Image](flaskblog/static/img/login.png?raw=true "Title") -->
### Checkup Page 
![Website Image](flaskblog/static/img/checkup.png?raw=true "Title")
### Diagnosed Disease 
![Website Image](flaskblog/static/img/diagnosis.png?raw=true "Title")
### User Helpguide
![Website Image](flaskblog/static/img/guide.png?raw=true "Title")
<!-- ### Terms and condition Page 
![Website Image](flaskblog/static/img/terms.png?raw=true "Title") -->
### FAQ Page 
![Website Image](flaskblog/static/img/faq.png?raw=true "Title")
### Emergency Helpline Numbers
![Website Image](flaskblog/static/img/number.png?raw=true "Title")

<a id="learning"></a>
## 💡 Learnings
- Enhancing designing and graphic skills by accomodating javascript bootstrap library.
- Incorporating on scroll triggers for different elements using javascript and CSS.
- Integrating machine learning model with the web application.
- To call an API and display data onto our website.
- Implementing dialogflow bot into our web application with the help of kommunicate.
- Successfully deploying a web application on Heroku platform.

<a id="challenges"></a>
## 💡 Challenges faced
- Had technical setup issue related to sklearn library while developing the project.
- Gathering dataset for the diseases and their treatment.
- Diﬀiculty with model building for disease prediction and integrating it with the web application.
- Faced problem while gathering illsutrations and graphical representation for the related content of the website.
- Finding free API that met all of our requirements.
- Ran into multiple error while deploying the app.

<a id="scope"></a>
## 🚧 Future Scope/ What's next?

- [ ] Implementing disease prediction using symptoms through Whatsapp using API calls.
- [ ] Make website responsive for multiple devices and develop mobile application for the same.
- [ ] Seeking online medical help via a calling feature.
- [ ] Providing latest health-related news as html template on the email of subscribed users.
<!-- - [ ] Seeking online medical help via a calling feature.
- [ ] Providing information of nearby healthcare center to the user. -->
<!-- - [ ] The model will not only predicts the disease but also suggests specialization that is meant to deal with the treatement.
- [ ] To maintain the history of the predicted disease of the user. -->

<a id="resources"></a>
## 📚 Resources

- [HTML Documentation](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS Documentation](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [Tailwind CSS Cheat Sheet](https://nerdcave.com/tailwind-cheat-sheet)
- [JS Documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [Bootstrap Documentation](https://getbootstrap.com/docs/4.1/getting-started/introduction/)
- [Flask Documentation](https://flask.palletsprojects.com/en/2.0.x/)
- [Jinja Documentation](https://jinja.palletsprojects.com/en/3.0.x/)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Numpy Documentation](https://numpy.org/doc/)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)
- [GSAP](https://greensock.com/docs/v3/GSAP)
- [Map-Box](https://www.mapbox.com/)
- [NewsApi](https://newsapi.org/)
- [Disease Dataset](https://impact.dbmi.columbia.edu/~friedma/Projects/DiseaseSymptomKB/index.html)


<a id="setup"></a>
## ⚙️ Set Up

Take These Steps to configure the Project :

* Clone The Repository
```
git clone https://github.com/samya02/WE-Project-Disease-Predictor
```

* Create a virtual environment(Code is for Windows Only)
```
virtualenv venv 
```

* Download all required modules using
```
pip install -r requirements.txt
```

* Create database by running the following command using python in command prompt
```
from flaskblog import db
db.create.all()
exit()
```

*  Run the app.py file in command prompt 
```
python app.py
```
* Now Head on to ['http://127.0.0.1:5000/'](http://127.0.0.1:5000/)


<a id="authors"></a>
## 💻 Authors

Contributors names and contact info :

Punerva Singh(Frontend Development)<br> 
[@Linkedin](https://www.linkedin.com/in/punerva-singh-958305204)
<br>
[@Github](https://github.com/punervasingh)
<br>

Samya Jain(Backend Development)<br>
[@Linkedin](https://www.linkedin.com/in/samya-jain-a68443204)
<br>
[@Github](https://github.com/samya02)
<br>



<a id="bug"></a>
## 🐛 Bug Reporting
Feel free to [open an issue](https://github.com/samya02/WE-Project-Disease-Predictor/issues) on GitHub if you find bugs.

<a id="feature-request"></a>
## ⭐ Feature Request
- Feel free to [open an issue](https://github.com/samya02/WE-Project-Disease-Predictor/issues) on GitHub to add any additional features you feel could enhance this project.  

