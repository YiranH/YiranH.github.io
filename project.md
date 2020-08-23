---
title: "Projects"
permalink: "/projects/"
layout: page
---

## Software Development Projects
* The Tracking Module of AI Monitoring and Management System (May - Aug. 2020)

    _Intuit Inc., Software Engineer Intern_

    * Designed and built the tracking module of AI monitoring and management system to improve the quality and maintenance of AI model assets by tracking parameters, metrics and Git commits of model, and provide a collective view of model details.
    * Established development environment in Docker containers, deployed application and database on AWS.
    * Built tracking server to track Git commit details associated with each model using Flask framework, integrated MLflowtracking component to enable the tracking of model parameters and metrics.
    * Set up GitHub webhooks to deliver Git commit data to server, created REST APIs to store and retrieve Git commit data.
    * Used MySQL database to store tracking data, with SQLAlchemy to create queries and Alembic to manage schema migration.
    * Designed user interface using React and Redux, adopted Redux Thunk middleware to handle asynchronous requests.
    * Achieved 90% test coverage by unit, integration and E2E testing using Pytest and Jest.

* [Collaborative Text Editor](https://shielded-brushlands-62750.herokuapp.com/) (Feb. - Apr. 2020)
    * Built a text editor with scalable decentralized real-time collaboration features and deployed application on Heroku.
    * Used Node.js and Express framework for back end and Handlebars.js for front end.
    * Set up server to connect client nodes to reduce latency, adopted Socket.io to enable real-time bi-directional communication.
    * Implemented Conflict-Free Replicated Data Type for data transmission to achieve concurrency control and consistency maintenance.

* [Self-Evaluation System for Graduate Algorithm Course]() (Sept. - Dec. 2019)
    * Developed a self-evaluation website for a graduate course using Ruby on Rails framework and MVC architecture, withfunctions of adding questions, selecting question topics, taking tests, and resetting passwords.
    * Set up application on AWS Cloud9 and deployed application on Heroku with PostgreSQL as database.
    * Designed user interface using HTML, CSS and JavaScript, applied MathJax to display mathematical notation in browsers.
    * Utilized Agile development life cycle, managed projects in Pivotal Tracker with user stories and customer issues.
    * Applied Behavior and Test Driven Development methodology and achieved 98.4% test coverage by testing with RSpec.

* Web Tracking Service (Jan. - Feb. 2019)
    * Created a web tracking service using Java where user can track the modification of registered static web pages.
    * Built web API using AWS Lambda and API Gateway for users to register URLs and store corresponding web pages in S3.
    * Set up backend service on AWS EC2 instance to detect changes of web pages and save the latest version in S3.



## Data Science Projects
* Facial Expression Detection (Feb. - Apr. 2020)
    * Developed models in Python to detect human facial expression from videos in real time.
    * Created dataset using STAIRS actions dataset, extracted face, hand and pose landmarks using OpenPose.
    * Built CNN and LSTM models with Keras, used MLflow to track model performance, achieved 88.6% acccuracy on test set.

* [Detecting Hateful Users on Twitter](https://sites.google.com/tamu.edu/hatedetector/home) (Sept. - Dec. 2019)
    * Implemented a system in Python to detect hateful users by tweets and replies to help create a friendly internet environment.
    * Fine-tuned Doc2Vec and Bert models with 24783 labeled tweets and applied models to label 20 million original tweets.
    * Applied clustering algorithms to classify users and achieved the highest accuracy of 76.26% on test set.

* [Implementation of Viola-Jones Algorithm for Face Detection](https://github.com/YiranH/Viola_Jones_649.git) (Sept. - Dec. 2019)
    * Implemented Viola-Jones Algorithm in Python and achieved a highest accuracy of 83.48\% on a test set of 2500 images.
    * Built Adaboost detectors to detect facial images by selecting classifiers from over 26000 Haar features.
    * Constructed a cascade classifier to filter Adaboost detection result and improved the accuracy by 4.99\%.