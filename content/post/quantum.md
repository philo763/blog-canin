---
title: "Quantum computing - Learning platform"
date: 2018-12-28
categories:
- learning platform
- UTC
tags:
- JS
- quantum computing
thumbnailImagePosition: left
thumbnailImage: "img/bloch_sphere.png"
showSocial: false
showPagination: false
draft: true
---

Check out my learning platform to get familiar with the concepts of `Quantum Computing` developed using [*Reveal.js*](https://revealjs.com/#/).
<!--more-->

# Context

The learning platform was built during a university project (Class - *TX*) over a period of 6 months.


<br>

{{< blockquote "R. Feynman" "1981" >}}
[...] Nature isn’t classical [...] and if you want to make a simulation of Nature, you’d better make it quantum mechanical, and by golly it’s a wonderful problem, because it doesn’t look so easy.
{{< /blockquote >}}

<br>

# Introduction

*Kurzgesagt - In a Nutshell* presents **Quantum Computers Explained – Limits of Human Technology** :

<br>

{{< youtube JhHMJCUmq28 >}}


#  Content

The content provides a quick introduction to the topics mentioned above :

---

* **Quantum mechanics basics**
  * Introduction to Vectors
  * Linear Independance
  * Span and Basis
  * Dimensions
  * Linear Transformations
  * Column Vectors and Matrices
  * Inner Product
  * Multiplying Vectors and Matrices
  * Projection Operator
  * Qubit !
* **Commonly used Quantum Logic Gates**
  * Hadamard (H) gate
  * Pauli-X Gate
  * Pauli-Y Gate
  * Pauli-Z (R<sub>π</sub>) Gate
  * Controlled (cX cY cZ) gates
  * T Gate
  * S Gate
  * Measurement
* **Quantum Cryptography**
* **Quantum Algorithms**
  * Shor's Algorithm
* **Physical Implementations**
* **Error Rate & Corrections**
* **Ethics**

---

{{< alert warning >}}
The content of the platform is still in progress and parts are missing..
{{< /alert >}}


# Interested in Quantum computing ?

### IBM Q Experience

You can run algorithms and experiments on IBM's quantum processor via IBM Cloud.

{{< alert success >}}
Link to [IBM Q Experience](https://quantumexperience.ng.bluemix.net/).
{{< /alert >}}


# Website

{{< alert success >}}
Link to the live [platform](https://gitlab.utc.fr/hvergnol/quantum).
{{< /alert >}}

{{< alert danger >}}
Not working yet..
{{< /alert >}}


# Screenshots

![screenshot 1](http://static.vergnol.eu/img/quantum1.png)

![screenshot 1](http://static.vergnol.eu/img/quantum2.png)


# Repository

{{< alert success >}}
Link to the [gitlab repo](https://gitlab.utc.fr/hvergnol/quantum) hosting the source code.
{{< /alert >}}

### Install a local version of the plateform

To build a local version of the plateform, please follow these instructions :


### Instructions

{{< codeblock "install_quantum.sh" "bash" >}}

# clone the Repository
git clone https://gitlab.utc.fr/hvergnol/quantum quantum

cd quantum/quantum

# Launch the plateform
firefox index.html

{{< /codeblock >}}


&rightarrow; The application is then available in your browser !



# Mentions

> Use of the HTML Presentation Framework [`Reveal.js`](https://revealjs.com) developed by *Hakim el Hattab*.

> The code is available [here](https://github.com/hakimel/reveal.js).
