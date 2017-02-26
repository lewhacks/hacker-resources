# hacker-resources
Stuck not knowing what to do? Here are some gr8 resources for the aspiring developer!

---

## Table of Contents

1. [What is a hackathon?](#what)
2. [Beginner Resources](#beginner)
    1. [Using Git and Github](#git)
    2. [Linux? What is that?](#linux)
    3. [Python](#python)
      1. Web Development
      2. Game Development
      3. Data Science
      4. ...more to come!
    4. [HTML/CSS](#html)
      1. Bootstrap and Responsive Web Design
      2. How to publish your website
      3. Great domain and hosting providers
      4. ...more to come!
    5. [Ruby](#ruby)
    6. [Javascript](#javascript)
    7. [Tips and Tricks](#tips)
      1. What should I use to write code?
      2. What operating system should I rely on?
3. [General Resources](#general)

---

## What is a hackathon? <a name="what"></a>

### "Hacking"? I don't like the sound of that.

A hackathon is an event where developers, makers, and designers come together, and build amazing technology in a very short amount of time, usually 12 to even 48 hours. With these projects, not only are they able to win prizes, but create something revolutionary that can help change the world. Usually occuring during the weekend, hackathons provide free swag, great food for all, and a great environment for developers.

### Wait, do I have to meet other ... people???

When you go to a hackathon, you often form teams with others, whether they are with people you know, or strangers you never met. Although this may seem daunting and scary, forming a team is an integral part of a hackathon, and through it, not only can you network with amazing people, but also learn a thing or two from them.

### But what if I'm only in high school?

Student hackathons are usually the most prevalent. One of the most prominent organization / league for hackathons is [Major League Hacking](https://mlh.io/), help sponsor hackathons big and small, providing them the resources to become an amazing event.

Whether you decide to attend a small hackathon (like [lewHacks()](http://lewhacks.tech/)) or a large hackathon (like [Pennapps](http://2017w.pennapps.com/)), always make sure to have fun, and let your creativity run wild!

---

## Beginner Resources <a name="beginner"></a>

With the growing impact technology has in the world, getting into coding and programming has never become easier. With the vast availability of not only __great__, but also __free__ and __open-source__ resources, it is nearly impossible __NOT__ to learn code.

### Using Git and Github <a name="git"></a>

You see all these programmers and developers using this "Github". What is Github? What is git? What does this all mean?

__Git__, developed approximately a decade ago, is what is known as a __version-control__ system. Linux Torvalds, the father of the Linux Operating system, built Git so that other developers could work together and push code to the Linux kernel, as it was an open-source project. Git made sure that developers who worked together on a single project could effectively make changes to it, and fix any conflicts that occur when they do.

Eventually, __Github__ would come. What's the difference between Git and Github? Essentially, Git was developed as a program and application, specifically for Linux systems. However, __Github__ was developed as an online hosting service for Git projects. Each project was known as a __repository__. In fact, what you are reading right now is documentation that is part of a Github repository.

Here is this process shown visually. Alan and Derek are two developers working on the next Twitter app. They both live in different parts of the world, and they find that emailing each other files of all the code was not only inefficient and time-wasting, but it also lead to problems in the code. Alan was clearly a better developer than Derek, as he had a different (better) style of writing code. Their partnership in the project lead to disastrous results in the app, and it didn't work out. However, in Git, that was different.

When you initialize an empty repository on Github, you start on what is known as a `master` branch. This `master` branch is where you push all the changes you made to your code.

Let's say Alan writes one file. He then writes a __commit__, which essentially is a message stating what has been changed, and pushes it onto that `master` branch.

    Alan (file.js) Commit: Added file.js file.
          |
    ----------------------------------------

After he pushes it, he enables Derek to have access to that repository. Derek _clones_ the repo, meaning he takes the code on Github's servers, and essentially downloads a copy of it so that he can access it locally.
He adds several files to it, writes a commit and pushes it onto the `master` branch.

    Alan (file.js)    
          |             
    ----------------------------------------
                      |
                    Derek (blah files) Commit: Added new files

Alan wants to work on that again. Therefore, he does a _pull_ on the code, meaning that he grabs the most recently pushed copy of the code, and replace it with the one he has currently. Of course, Alan may need to do a `stash`, or `merge` with a prior commit, but I won't get into that today.

Overall, git + github are great tools for developers who want to work with other developers, as well as make their code available online as open-source, enabling others to utilize it, and send issues and __pull requests__, which are essentially commits from developers who do not have access to the project, but want to provide code fixes, or any suggestions for improvement.

Still confused? Here are some additional resources.

* [Video - What is Github](https://www.youtube.com/watch?v=w3jLJU7DT5E)
* [ What Exactly Is GitHub Anyway?](https://techcrunch.com/2012/07/14/what-exactly-is-github-anyway/)
* [Git Tutorial](https://www.youtube.com/watch?v=9GKpbI1siow)
* [Github - Hello World](https://guides.github.com/activities/hello-world/)
* [Learn Git](https://www.codecademy.com/learn/learn-git)
* [Become a Git Guru](https://www.atlassian.com/git/tutorials)
* [Try Git](https://try.github.io/levels/1/challenges/1)
* [Git - Tutorial](http://www.vogella.com/tutorials/Git/article.html)

### Linux? What is that? <a name="linux"></a>


### Python <a name="python"></a>

Created by Guido van Rossum, Python can be considered one of the most beginner-friendly languages out there. Perfect for beginners who want to get involved into programming, and does not want to get trapped into the horrors of object-oriented programming.

* [Hitchhiker's Guide to Python](http://docs.python-guide.org/en/latest/)
* [Automate the Boring Stuff with Python](https://automatetheboringstuff.com/)
* [Sentdex's Python3 Basics Tutorial Series](https://www.youtube.com/playlist?list=PLQVvvaa0QuDe8XSftW-RAxdo6OmaeL85M)
* [Learn Python the Hard Way](https://learnpythonthehardway.org/book/)
* [learnpython.org](https://www.learnpython.org/)
* [Codecademy - Python](https://www.codecademy.com/learn/python)

There are definitely people with experience in Python, and want to build some cool stuff with it.

Want to make websites and applications with Python? __Flask__ and __Django__ got you covered.

Flask
* [Official Flask Docs](http://flask.pocoo.org/docs/0.12/)
* [Flask - Fullstack Python](https://www.fullstackpython.com/flask.html)
* [The Flask Mega-Tutorial](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world)

Django
* [Getting Started with Django](https://www.djangoproject.com/start/)
* [The Django Book](http://djangobook.com/)
* [Stackoverflow - Whats the best way to start learning django?](http://stackoverflow.com/questions/4048973/whats-the-best-way-to-start-learning-django)

Interested in building games? Python also got you covered with their __pygame__ library!

* [Pygame Tutorials](http://pygametutorials.wikidot.com/)
* [Invent with Python](https://inventwithpython.com/makinggames.pdf)
* [thenewboston's Pygame Playlist](https://www.youtube.com/watch?v=K5F-aGDIYaM&list=PL6gx4Cwl9DGAjkwJocj7vlc_mFU-4wXJq)

Want to work with data and build applications that work with data? Python is a suitable language for data, comparable with R and MATLAB.

* [Intro to Python for Data Science](https://www.datacamp.com/courses/intro-to-python-for-data-science)
* [Applied Data Science with Python Specialization](https://www.coursera.org/specializations/data-science-python)
* [A Complete Tutorial to Learn Data Science with Python from Scratch](https://www.analyticsvidhya.com/blog/2016/01/complete-tutorial-learn-data-science-python-scratch-2/)
* [Dataquest - Learn data science](https://www.dataquest.io/)
* [A modern guide to getting started with Data Science and Python](http://twiecki.github.io/blog/2014/11/18/python-for-data-science/)

### HTML/CSS <a name="html"></a>

So you decided to go the path of the __Hyper Text Markup Language__. Interested in building websites? We got you covered.

* [Interneting is Hard](https://internetingishard.com/)
* [Learn HTML and CSS](https://www.codecademy.com/learn/learn-html-css)
* [W3Schools - HTML5 Tutorial](https://www.w3schools.com/html/)
* [Learn to Code HTML & CSS](http://learn.shayhowe.com/html-css/)
* [General Assembly - Learn to code awesome websites in HTML, CSS, and JavaScript](https://dash.generalassemb.ly/)

Hmmm, I mean, I can build a simple website, but how do I add design and _flavor_ to it?

Introducing __Bootstrap.css.__ Bootstrap is a great framework in CSS that enables you to make __responsive__ website designs. Not only are your websites going to look beautiful, but they are also responsive, and will not look like poop on a mobile phone or tablet.

* [W3Schools - Bootstrap 3 Tutorial](https://www.w3schools.com/Bootstrap/)
* [Blasting Off with Bootstrap](https://www.codeschool.com/courses/blasting-off-with-bootstrap)
* [Offical Getbootstrap Docs](http://getbootstrap.com/css/)
* [Derek Banas - Learn Bootstrap in One Video](https://www.youtube.com/watch?v=gqOEoUR5RHg)

Now I have a good website. How do I deploy it so that it has a URL? Of course, what you may have built is a __static__ website. A static website is a site that does __NOT__ have login forms, as well as anything that will require you to setup databases and storage systems for data, like user login. Of course, that does not mean that a static website is useless. They are perfect for people who want showcase their portfolio, their projects, and themselves. Building websites with a focus on design (such as with Bootstrap), and not really all the extra server and database gunk, is known as __front-end__ web development. Those who focus on building the stuff that happen in the __back__, such as the servers and the data from users, are known as __back-end__ developers. People that have expertise in BOTH front and backend development are known as __full-stack__ developers.

What about __domain__ and __web hosting__? What is the difference between those?

Web hosting is basically any server where you can plop your website. Of course, there are various types of hosting, and services that enable you to host a website. __Amazon Web Services__ is a quite popular one, but you can even host your own website on your own physical server. Web hosting is great for people who are full-stack developers, and have a website that has a lot of functionalities, such as login forms.

A domain is basically an address that identifies your website. It provides the URL and DNS that makes your site accessible to the public. When people often have web hosting, they also need a domain that points to the web hosting, so that when people visit the site, they don't have to type `wwww.something-webservice-blah-blah.webserverprovider.com`, but instead `mywebsite.com`.

If you want deploy a static site without having to pay for hosting and the domain, doing it through __Github Pages__ is a good option.

* [Github Pages](https://pages.github.com/)
* [A Guide to Using Github Pages](https://www.thinkful.com/learn/a-guide-to-using-github-pages/)
* [Github Guides](https://guides.github.com/features/pages/)
* [Creating and Hosting a Personal Site on GitHub](http://jmcglone.com/guides/github-pages/)

Of course, if you want to have a cool official domain name, there are a few great and hackathon-friendly providers.

* [Domain.com](http://www.domain.com/)
* [Get.tech](http://get.tech/)
* [Namecheap](https://www.namecheap.com/)

...

### Ruby <a name="ruby"></a>

### Javascript <a name="javascript"></a>

---

## General Resources
Looking for inspirations? Maybe developer tools? Free stuff? Resources to help with your next project?

* [free-programming-books repo](https://github.com/vhf/free-programming-books/blob/master/free-programming-books.md)
* [free-for-dev repo](https://github.com/ripienaar/free-for-dev)
* [Open Source Guides](https://opensource.guide/)
*
