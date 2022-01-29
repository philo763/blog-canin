---
title: "Tutut - Carpooling app"
date: 2017-06-11
categories:
- web application
- UTC
tags:
- python
- django
thumbnailImagePosition: left
thumbnailImage: "img/tutut.png"
showSocial: false
showPagination: false
draft: true
---

Check out `Tutut`, a carpooling app written in *Python* using [*Django*](https://www.djangoproject.com/).
<!--more-->


# Context

We had the idea to write a carpooling app between the two main study sites of the University of Technology of Compiegne. As far as of now, every carpool request and offer are posted on a Facebook group, which is constantly flooded with information coming from every direction.

# The origin

`Tutut` was originally created at a hackathon by a team of 4 fellows : Samy N. + William B. + Yanis O. and myself. We had 48 hours to come up with a running application starting from scratch. we chose to develop our own MVC framework to create a webapp. Unfortunately,

# What now ?

I developped Tutut on my own starting from scratch and developing when I had the time to.
The first release of the app was in March 2018. But unfortunately, the University server couldn't hold the application due to a lack of support of Django technology.

# Functionalities

* Share a ride.
* Book a ride.
* Add a vehicle.
* Manage a profile.
* Eco-points system for rewards.

# Technical Functionalities

* LDAP / CAS integration.
* SMTP integration.

# Possible features ?

* Docker version of the app.
* SMS support using twilio.


# Screenshots

![screenshot 1](showcase.png)

![screenshot 1](img/showcase.png)

# Repository

&rightarrow; [Link to the gitlab repo](http://xxx.yyy)

## Install a local version of the app

To build a local version of the app, please follow these instructions :


## Prerequisites

* Django version : **1.9.2**
* pip installed

## Instructions

{{< codeblock "tutut.sh" "bash" >}}

# clone the Repository
git clone https://xxx.yyy tutut

cd tutut

# Install the requirements
pip install -r requirements.txt

# Launch the Django server
python3 manage.py runserver

{{< /codeblock >}}


&rightarrow; The application is available at [localhost:8000](localhost:8000).
