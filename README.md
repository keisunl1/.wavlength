# .wavlength
This repository will contain all software design used for the application .wavlength.

We will be using the following softwares/APIs: 

1. Spotify API

2. Flutter - Frontend software

3. MongoDB - Backend software 

4. Django - Web API

5. AWS/Azure - Cloud-based platform 

6. Python/R - for data analysis and visualization, and access to libraries such as scikit-learn, numpy, pandas

7. Tensorflow - for ML application 


What we need to do:
   
   1. Develop a system for analyzing users' Spotify listening data to determine their personality type or persona. This could involve using natural language processing techniques to analyze song lyrics and artist bios, as well as machine learning algorithms to identify patterns in listening behavior.
   
   2. Design a user interface for the app that allows users to input their Spotify information and view their persona. You could also include a feature for users to edit their persona if they disagree with the analysis.
   
   3. Build a database to store users' persona information and match users based on their persona. You could use a matching algorithm that takes into account both personality and interests.
   
   4. Implement a messaging system for users to communicate with each other.

Technologies:

  Backend development: Use a programming language such as Python or Java to build the server-side logic of the app. This would include making the API that connects the front end and the back end and handle the data flow.

 1. Database management: Need a database management system to store and retrieve users' personal information and match users based on their persona. We have decided to use (1) MongoDB and (2 - backup) Firebase:
 
 2. MongoDB uses a document-based data model, which allows for more flexibility in storing and querying data. This can be useful for storing complex and hierarchical data structures like Spotify profile information and persona data.

 3. Scalability: MongoDB is designed for horizontal scalability, which means it can easily handle large amounts of data and handle a large number of concurrent users. This can be useful for an app that is expected to grow in popularity and user base.

 4. Performance: MongoDB has a high-performance architecture, which can handle high write and read loads. It also supports indexing/sharding, which can improve query performance.
 MongoDB can be run on a variety of platforms including Windows, Mac, and Linux, and it also supports cloud-based deployment options like AWS, Azure, etc.

  Machine learning: Need to use machine learning algorithms to analyze users' Spotify listening data and determine their personality type or persona. Use libraries such as sci-kit-learn or Tensorflow for this.

   1. Natural Language Processing: Use NLP techniques to analyze song lyrics and artist bios to help determine the user's persona. Use libraries such as NLTK or spaCy for this.

  Frontend development: Need to use a programming language to build the user interface of the app. We have decided to use (1) Flutter and (2 - backup) React Native:
  We want it to be able to work across Android and iOS platforms
  Flutter uses a reactive programming model and uses its own widgets which are rendered directly by the GPU, resulting in faster performance

   1. Hot Reload: Flutter's "hot reload" feature allows developers to make changes to the code and see the changes reflected in the app in real-time, which can speed up the development process.
      a. Customizable widgets → good for designing the user interface of the app
      b. Flutter is open source → no license fees
      c. Community → tutorials, documentation, plugins which can make the development easier

  API: We would need to use Spotify Web API to collect user's listening data. We have chosen to use (1) Django and (2 - backup) Flask

  Python: as Django is built on python, it allows to take advantage of the vast python ecosystem and its libraries.

   1. Rapid Development: Django is a high-level web framework that allows for rapid development and prototyping of web applications. It comes with a lot of built-in functionality, such as an ORM, admin panel, and security features, which can save time and resources in development.

   2. Scalability: Django is designed to handle large amounts of traffic and can be easily scaled up or down as needed. This can be useful for an app that is expected to grow in popularity and user base.

   3. Well-organized: Django follows the model-view-controller (MVC) pattern, which promotes a clean and organized codebase. This can make it easier to maintain, test and debug your code.

  Cloud services: Need to use a cloud platform, such as AWS or Azure, to host the app and its associated services. This includes using services like storage, databases, authentication and hosting
