## Phishing Domain Detection
Phishing is an online threat where an attacker impersonates an authentic and trustworthy organization to obtain sensitive information from a victim.

A technique for attempting to acquire sensitive data, such as bank account numbers, through a fraudulent solicitation in email or on a web site, in which the perpetrator masquerades as a legitimate business or reputable person.

## Life cycle of the project:

Understanding The Problem.
Reading Dataset Into The Working File.
Getting Familiar With The Dataset.
Exploratory Data Analysis.
Data Pre-Processing.
Model Training.
Choose Best Model.

## Aproach:

For Feature Engineering show:-
1. URL-Based Features

Uniform Resource Locator (URL) is created to address web pages. The figure below shows relevant parts in the structure of a typical URL.

![Phishing diagram](https://github.com/nevetto/phishing_domain_detection/assets/82023798/5901ed83-9f19-479c-918a-036e0bd61e17)

URL-Based Features
URL is the first thing to analyse a website to decide whether it is a phishing or not. As we mentioned before, URLs of phishing domains have some distinctive points. Features which are related to these points are obtained when the URL is processed. Some of URL-Based Features are given below.

* Digit count in the URL
* Total length of URL
* Checking whether the URL is Typosquatted or not. (google.com → goggle.com)
* Checking whether it includes a legitimate brand name or not (apple-icloud-login.com)
* Number of subdomains in URL
* Is Top Level Domain (TLD) one of the commonly used one?



2. Domain-Based Features
3. Page-Based Features
4. Content-Based Features