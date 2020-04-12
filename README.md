# Favor
[![Build Status](https://travis-ci.com/eric-newcomer/favor.svg?token=ad6LGj5Vax5svVMzEGdd&branch=develop)](https://travis-ci.com/eric-newcomer/favor)

## Brief Description of Project
Favor is an app that helps college students get things done by providing a non-monetary economy where students can trade skills for services. Students offer Favors (services) that other students can sign-up for. In doing so, they earn Favors, which they can use to "buy" Favors from other students. The goal of our app is to increase student interaction and improve student relations by valuing all forms of work and providing service options for those who cannot afford professional services.  

## Our Tech Stack and Language
We used Django, a Python web framework, for our project. Our frontend was built using HTML, CSS, and JavaScript, while our backend was built using Python.

## 5 Most Helpful Resources for Getting Started
There are a plethora of resources online for learning Django. After trying many tutorials and 'Getting Started' pages, these are the resources we recommend.

1. [Writing your first Django app, by Django](https://docs.djangoproject.com/en/3.0/intro/tutorial01/)
The Django documentation is a great resource for getting started, and is a tried and true starting point for total beginners. It teaches you the Django framework by taking you through the process of building a Django web app (which I would argue is the best way to learn Django).
2. [Mozilla's Django Introduction](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Introduction)
Mozilla has a great Django tutorial that is similar to the tutorial by Django, in that it takes you through the steps of building a Django web application. It is different in that it is straight to the point (only includes pertinent information about building the application) and is easier to navigate (11 webpages, each with a relevant title, e.g. "Django Tutorial Part 9: Working with Forms" vs Django's "Writing your first Django app, part 7").
3. [Simple is Better than Complex](https://simpleisbetterthancomplex.com/)
SIBTC is a great resource that provides many articles written about more advanced Django topics with examples of each. Each article is easy to understand, yet provides enough detail about the topic to finish developing what you need to implement. I have never left this website without a solution to my Django problems. Thanks [Vitor](https://simpleisbetterthancomplex.com/about/)!
4. [Corey Schafer's YouTube Tutorials](https://www.youtube.com/watch?v=UmljXZIypDc&list=PL-osiE80TeTtoQCKZ03TU5fNfx2UY6U4p)
For those that are more inclined towards video tutorials, Corey Schafer is an excellent place to go. Whether you want to learn how to do something very specific in Django, or you want a fully-fledged "Let's build a Django web app" tutorial, Schafer's YouTube channel has the videos to watch. In addition to Django tutorials, Schafer is a great video resource for all things Python.
5. [freeCodeCamp Django Tutorial](https://www.youtube.com/watch?v=F5mRW0jo-U4)
FreeCodeCamp is a great resource for learning coding online. If you have an open 4 hours on your hands, they have a full 4-hour long Django course on YouTube to watch. They offer many courses on other frameworks as well, all for free. Check out their [website](https://www.freecodecamp.org/).

## UML Diagram
Our project follows the MVT (Model View Template) software design pattern, and common pattern for Django web applications. The Model helps access objects stored in our database, and serves as our data access layer. The Template is a collection of HTML files (with CSS and JS) that serves as our UI layer. The View contains our business logic, which interacts with our models and renders different templates. 

Below is a UML graph that models our MVT control flow. Our Model layer is in green, our Template layer is in blue, and our View layer is in yellow.
 
![favorUML](https://user-images.githubusercontent.com/20120289/76543397-b2964380-6443-11ea-9e53-eb97edaa739b.png)


## Task Flow Diagram
The following is a task flow diagram for a user of our application. 

![307taskflow](https://user-images.githubusercontent.com/20120289/76439934-6501d400-637a-11ea-9447-fb31b47f678f.png)
