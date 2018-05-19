# Hacker's Roadmap

## Table of Contents
* Full-Stack Web Development
	* Frontend Topics
		* [Basic Frontend Web Development](#basic-frontend-web-development)
		* [Intermediate Frontend Web Development](#intermediate-frontend-web-development)
		* [Advanced Frontend Web Development](#advanced-frontend-web-development)
	* [Backend Topics](#backend-web-development)
* [Data Science & Machine Learning](#data-science--machine-learning)

## Full-Stack Web Development
### Basic Frontend Web Development
#### Topics: HTML, CSS, Responsive Design, Javascript

0. [Introduction to Web Development](https://internetingishard.com/html-and-css/introduction/)
1. Learn HTML & CSS
	* Option 1:
		1. Learn HTML
			* [Introduction](https://internetingishard.com/html-and-css/basic-web-pages/)
			* [Links and Images](https://internetingishard.com/html-and-css/links-and-images/)
		2. Learn CSS
			* [Introduction](https://internetingishard.com/html-and-css/hello-css/)
			* [How to link CSS to your HTML](https://www.w3schools.com/css/css_howto.asp)
			* [Box Model](https://internetingishard.com/html-and-css/css-box-model/)
			* [Selectors](https://internetingishard.com/html-and-css/css-selectors/)
			* [Float](https://internetingishard.com/html-and-css/floats/)
			* [Positioning](https://internetingishard.com/html-and-css/advanced-positioning/)
	* Option 2: [Codecademy](https://www.codecademy.com/en/tracks/web)
2. Project: Build your personal website using just HTML/CSS! Don't worry about how it looks on mobile yet.
	* Use [Chrome Developer Tools](https://developer.chrome.com/devtools) to debug and edit your website in-browser
	* Don't worry if you don't know how to start! Revisit the tutorials and Google your questions! Starting is always the hardest part.
3. Responsive Web Design
	* [What does responsive mean?](https://www.w3schools.com/css/css_rwd_intro.asp)
	* [Examples of responsive web design](http://blog.froont.com/9-basic-principles-of-responsive-web-design/)
	* [What is Bootstrap?](https://stackoverflow.com/a/24783264)
	* Check out [Bootstrap Components](https://getbootstrap.com/docs/4.1/components/buttons)
		* Note: Bootstrap's documentation has example code snippets which show you how to use different components/widgets which you can just copy and paste into your code.
	* [Bootstrap Grids](https://youtu.be/VaW4na2qkwQ) Tutorial
	* [Bootstrap Nav Bar](https://youtu.be/L0uNai3XyKQ) Tutorial
4. Project: Upgrade your personal website to be responsive and use a nav-bar component!
	* Note: you can use different frontend frameworks such as [Foundation](https://foundation.zurb.com/), [Materialize](https://materializecss.com/), [SemanticUI](https://semantic-ui.com/), etc if you prefer.
5. Javascript
	* [Why JS?](https://www.thoughtco.com/what-is-javascript-used-for-2037679)
	* [Codecademy: Learn JS](https://www.codecademy.com/learn/introduction-to-javascript)
	* [Intro to the DOM](https://www.digitalocean.com/community/tutorials/introduction-to-the-dom)
	* Using JS to interact with a website	
		* [Interacting with Forms](https://www.codecademy.com/courses/html-javascript-css/0/1)
		* [Altering the DOM](http://eloquentjavascript.net/14_dom.html)
6. Project: Add animation, interaction, or a form to your website using Javascript!
7. Congratz! You know enough to build static frontend websites! Keep practicing by making websites till you feel more comfortable.

### Intermediate Frontend Web Development
This section is not required, but encouraged if time permits. If you do read anything here, read up on #2: Templating Engines and #4: Using CDNs.
1. [jQuery Overview](https://medium.com/front-end-hacking/jquery-109c5aebf028)
	* Note: jQuery is typically not used for large projects, and is seen more in small purely frontend projects. So having some idea of what it looks like is useful.
2. Templating Engines
	* [Introduction](https://www.htmlgoodies.com/beyond/javascript/js-ref/intro-to-javascript-template-engines.html)
	* [Handlebars.js Example](https://tutorialzine.com/2015/01/learn-handlebars-in-10-minutes)
3. CSS Preprocessor: Sass
	* [Sass](https://sass-lang.com/guide)
	* [Code Example](https://www.youtube.com/watch?v=b0d--jixRwg)
4. Using 3rd Party Javascript Libraries
	* Tutorial: [Isotope Tile Library](http://www.designlunatic.com/2011/08/isotope-tutorial/)
	* [Referencing External JS Libraries: CDNs](https://www.sitepoint.com/7-reasons-to-use-a-cdn/)

### Advanced Frontend Web Development
#### Topics: NPM, React.js, and Redux

0. Installation
	1. Install [`npm` and `node.js`](https://www.npmjs.com/get-npm)
1. Package/Dependency Managers
	* [What is `npm`?](https://docs.nodejitsu.com/articles/getting-started/npm/what-is-npm/)
	* [Basic `npm` commands](http://dreamerslab.com/blog/en/npm-basic-commands/)
2. React.js
	* [Introduction](https://www.codementor.io/johnkingzy/beginners-guide-into-reactjs-quick-dive-a6qa5medg)
	* [Hello, world Example](https://reactjs.org/docs/hello-world.html)
	* [Build a tic-tac-toe game](https://reactjs.org/tutorial/tutorial.html)
3. [`react-router`](https://medium.com/@pshrmn/a-simple-react-router-v4-tutorial-7f23ff27adf)
4. Project: Build a restaurant menu using React.js while trying to separate the view from the underlying data.
5. Redux
	* Introduction
		* [Part 1](https://www.smashingmagazine.com/2016/06/an-introduction-to-redux/)
		* [Part 2](https://code-cartoons.com/a-cartoon-intro-to-redux-3afb775501a6)
	* [Intro Code Example](https://dev.to/aurelkurtula/a-beginners-introduction-to-working-with-redux-in-react-13k)
	* Video Series: egghead.io
		* [Videos](https://egghead.io/courses/getting-started-with-redux)
		* [Additional Commentary](https://github.com/tayiorbeii/egghead.io_redux_course_notes)
	* Code Example: [Todo List](https://redux.js.org/basics/example-todo-list)
6. Project: Build a new react app using redux.

### Backend Web Development
1. [What is frontend & backend development](https://www.upwork.com/hiring/for-clients/frontend-vs-backend-web-development/)
2. [Client-server Architecture Introduction & Analogy](http://someshinyobject.com/posts/analogy-time-client-side-vs-server-side/)
3. [What is an API?](https://blog.codeanalogies.com/2018/02/27/web-apis-explained-by-selling-goods-from-your-farm/)
	* [Another Analogy](https://medium.com/@tyteen4a03/how-apis-work-an-analogy-for-dummies-ac6ee1d1671b)
4. [What is HTTP?](https://code.tutsplus.com/tutorials/http-the-protocol-every-web-developer-must-know-part-1--net-31177)
	* [`POST` vs. `PUT`](https://stackoverflow.com/questions/630453/put-vs-post-in-rest?noredirect=1&lq=1)
5. [What is REST?](https://stackoverflow.com/questions/671118/what-exactly-is-restful-programming?rq=1)
	* [What is the difference between HTTP & REST?](https://stackoverflow.com/questions/2190836/what-is-the-difference-between-http-and-rest)
	* [Designing a RESTful API: Best Practices](https://hackernoon.com/restful-api-designing-guidelines-the-best-practices-60e1d954e7c9)
	* [Designing a RESTful API: Another Example](https://making.lyst.com/2015/02/20/1-to-1-relationships-and-subresources-in-rest-apis/)
6. [Server-side Web Frameworks](https://developer.mozilla.org/en-US/docs/Learn/Server-side/First_steps/Web_frameworks)
7. [Databases: what & why](https://medium.com/omarelgabrys-blog/database-introduction-part-1-4844fada1fb0)
	* [Relational vs. non-relational databases](https://www.pluralsight.com/blog/software-development/relational-non-relational-databases)
8. Piecing everything together: [Full-Stack  Application Architecture](https://stackify.com/n-tier-architecture/)
9. Framework Specific Tutorials
	* Try choosing 1 particular framework (ie Node.js, Django, Ruby on Rails (RoR), etc.) and stick with it till you are comfortable with implementing the concepts you read about above. Then feel free to experiment with other frameworks to gain exposure in how they also implement the same thing.
	* Note: UCLA students tend to have more experience with Node.js due to UCLA ACM mentors/workshops/events, so it's recommended you learn Node.js first if you are a UCLA student for the larger support community.
	<!-- Resources on various web frameworks -->
	| Node.js | Django | RoR |
	|---------|--------|-----|
	| [Installation](https://nodejs.org/en/)         |[Installation](https://docs.djangoproject.com/en/2.0/intro/install/)        |[Installation](http://installrails.com/)
	| [Video Tutorials](https://www.youtube.com/playlist?list=PL55RiY5tL51oGJorjEgl6NVeDbx_fO5jR)         |[Official Tutorials: Part 1 - 7](https://docs.djangoproject.com/en/2.0/intro/tutorial01/)        |[Michael Hartl's RoR Book](https://www.railstutorial.org/book)     |
	| [Build a Web API](https://scotch.io/tutorials/build-a-restful-api-using-node-and-express-4)         |[Build a Web API](https://codeburst.io/building-an-api-with-django-rest-framework-and-class-based-views-75b369b30396)        |[Build a Web API](https://scotch.io/tutorials/build-a-restful-json-api-with-rails-5-part-one)     
	| [Build an online shopping cart](https://www.youtube.com/playlist?list=PL55RiY5tL51rajp7Xr_zk-fCFtzdlGKUp)         |[Build a blog Tutorial](https://tutorial.djangogirls.org/en/)        |     |

## Data Science & Machine Learning
1. [Learn Python](https://www.codecademy.com/learn/learn-python)
2. Setup [`virtualenv`](https://virtualenv.pypa.io/en/stable) to create and work in a Python virtual environment
	* [Why use it?](https://www.dabapps.com/blog/introduction-to-pip-and-virtualenv-python/)
	* [How to use `virtualenv`](http://www.simononsoftware.com/virtualenv-tutorial/)
	* What is `requirements.txt`?
		* [A Better `pip` Workflow](https://www.kennethreitz.org/essays/a-better-pip-workflow)
		* [`pip freeze`](https://websauna.org/docs/tutorials/deployment/freeze.html)
3. [Introduction to `pandas`](https://www.datacamp.com/community/tutorials/pandas-tutorial-dataframe-python)
	* Note: you can follow along with as much of the tutorial as you want till feeling comfortable with Pandas
4. Introduction to `numpy`
	* [Part 1](https://hackernoon.com/introduction-to-numpy-1-an-absolute-beginners-guide-to-machine-learning-and-data-science-5d87f13f0d51)
	* [Part 2](https://hackernoon.com/introduction-to-numpy-2-an-absolute-beginners-guide-to-machine-learning-and-data-science-967b21e3542a)
4. [Matplotlib Tutorial: Political Tweets](https://www.dataquest.io/blog/matplotlib-tutorial/)
5. Machine Learning Concepts
	* Introduction:
		* [A visual introduction](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/)
		* [A more in-depth introduction](https://www.digitalocean.com/community/tutorials/an-introduction-to-machine-learning)
	* Linear Regression
		* [Introduction](https://medium.com/simple-ai/linear-regression-intro-to-machine-learning-6-6e320dbdaf06)
		* [Cost Functions & Gradient Descent](https://medium.com/@lachlanmiller_52885/machine-learning-week-1-cost-function-gradient-descent-and-univariate-linear-regression-8f5fe69815fd)
		* [More on gradient descent & overfitting](https://hackernoon.com/supervised-machine-learning-linear-regression-in-python-541a5d8141ce)
		* [Code Example](http://scikit-learn.org/stable/auto_examples/linear_model/plot_ols.html)
	* K Nearest Neighbors (kNN)
		* [Introduction](https://www.youtube.com/watch?v=44jq6ano5n0)
		* [Terminology, Applications, and Trade-offs](https://medium.com/@adi.bronshtein/a-quick-introduction-to-k-nearest-neighbors-algorithm-62214cea29c7)
		* [Algorithm Visualization](https://akash-goswami.github.io/knn-what-how-why/)
		* Code Example: [Breast Cancer](https://www.youtube.com/watch?v=1i0zu9jHN6U)
		* Code Example: [Iris Flower](https://kevinzakka.github.io/2016/07/13/k-nearest-neighbor/)
	* Support Vector Machines (SVM)
		* [Introduction](https://blog.statsbot.co/support-vector-machines-tutorial-c1618e635e93)
		* [Code Example](https://pythonprogramming.net/support-vector-machine-svm-example-tutorial-scikit-learn-python/)
	* Logistic Regression
		* [Introduction](https://www.quora.com/What-is-logistic-regression/answer/Thirumal-Venkat-1?share=b8bc2ce1&srid=aP23)
		* [Sigmoid Function & Mathematical Introduction](https://machinelearningmastery.com/logistic-regression-for-machine-learning/)
		* Code Example: [Glass Identification](http://nbviewer.jupyter.org/github/justmarkham/DAT8/blob/master/notebooks/12_logistic_regression.ipynb)
	* K-Means
		* [Introduction](https://www.datascience.com/blog/k-means-clustering)
		* Video: [Clustering Introduction](https://www.youtube.com/watch?v=ZueoXMgCd1c)
		* [K-Means vs. kNN](http://abhijitannaldas.com/kmeans-vs-knn-in-machine-learning.html)
		* Video Series: Code Example
			1. [Part 1](https://www.youtube.com/watch?v=8p6XaQSIFpY)
			2. [Part 2](https://www.youtube.com/watch?v=j6jstahQp2A)
		* [Elbow method](https://en.wikipedia.org/wiki/Elbow_method_(clustering))
		* Code Example: [Self-implementation of Clustering](https://mubaris.com/2017/10/01/kmeans-clustering-in-python/)
		* Additional Topics
			* Principal Components Analysis: Dimensionality Reduction
	* Decision Trees
		* [Introduction](https://chunml.github.io/ChunML.github.io/tutorial/Decision-Tree/)
		* Code Example: [Iris Flower](http://chrisstrelioff.ws/sandbox/2015/06/08/decision_trees_in_python_with_scikit_learn_and_pandas.html)
		* Additional Topics
			* Entropy
			* Information Gain
	* Neural Networks
		* [Introduction](https://medium.com/learning-new-stuff/how-to-learn-neural-networks-758b78f2736e)
		* [TensorFlow Tutorial](http://adventuresinmachinelearning.com/python-tensorflow-tutorial/)
6. [Andrew Ng's Stanford Coursera Course](https://www.coursera.org/learn/machine-learning) for more theory/math
7. Guided Data Cleaning Project
    * [Video Game Reviews](https://www.dataquest.io/blog/pandas-python-tutorial/)
    * [Thanksgiving Foods](https://www.dataquest.io/blog/pandas-tutorial-python-2/)
8. Guided Data Storytelling Projects
    * [NYC Education](https://www.dataquest.io/blog/data-science-portfolio-project/)
    * [Fannie Mae Loan Foreclosure](https://www.dataquest.io/blog/data-science-portfolio-machine-learning/)
	* Video Series: [Predicting the stock market](https://pythonprogramming.net/data-acquisition-machine-learning/)
9. Do your own project!
	* Choose a dataset from [Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets), clean the data, try to extract meaning/trends, and make predictions and classifications similar to the guided projects above.
10. Congratz, you've learned and done enough to gain enough knowledge to onboard to more complex data science and machine learning projects in the future!