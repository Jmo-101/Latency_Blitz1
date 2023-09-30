# Latency_Blitz1

# Latency Issue Resolution for Nike's URL Shortener Application

## About
This repository provides insights into resolving a latency issue in Nike's URL shortener application. The document outlines the problem faced, the solution implemented, and the rationale behind the chosen approach.

## The Story
“Nike emailed you about the URL shortener. In Nike’s email, Nike mentioned customers are complaining about the amount of time it takes to load their webpages. Nike will like us to reduce the amount of latency customers are experiencing.”


## Problem
Users attempting to use the application were facing higher latency than normal. For a corporation like Nike, this increased latency translates into loss of profits, as they prioritize providing users with a seamless experience on their application.

<img width="200" alt="Screenshot 2023-09-29 at 9 51 44 PM" src="https://github.com/Jmo-101/Latency_Blitz1/assets/138607757/8f585755-0f33-4e96-a048-ccacdf3a2bf4">
<img width="300" alt="Screenshot 2023-09-29 at 10 11 17 PM" src="https://github.com/Jmo-101/Latency_Blitz1/assets/138607757/a8fdd266-9bd2-423e-9c49-03ba7b93b91e">


## Solution
To address the latency issue, we implemented a Content Delivery Network (CDN) in the form of Amazon CloudFront. The Purpose of using a CDN in our application is to make sure users get reduced latency when accessing the website. As a CDN its purpose is to be an intermediary between the application's server and the users. CloudFront caches and servers the user the static content of the webpage. When a user accesses the website, the CDN identifies the nearest server to the user's location. It then connects the user to the server, which in turn reduces the latency between the user and application 


