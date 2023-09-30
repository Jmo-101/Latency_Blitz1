# Latency_Blitz1

# Latency Issue Resolution for Nike's URL Shortener Application

## About
This repository provides insights into resolving a latency issue in Nike's URL shortener application. The document outlines the problem faced, the solution implemented, and the rationale behind the chosen approach.

## The Story
“Nike emailed you about the URL shortener. In Nike’s email, Nike mentioned customers are complaining about the amount of time it takes to load their webpages. Nike will like us to reduce the amount of latency customers are experiencing.”


## Problem
Users attempting to use the application were facing higher latency than normal. For a corporation like Nike, this increased latency translates into loss of profits, as they prioritize providing users with a seamless experience on their application.

## Solution
To address the latency issue, we implemented a Content Delivery Network (CDN) in the form of Amazon CloudFront. The Purpose of using a CDN in our application is to make sure users get reduced latency when accessing the website. As a CDN its purpose is to be an intermediary between the application's server and the users. CloudFront caches and servers the user the static content of the webpage. When a user accesses the website, the CDN identifies the nearest server to the user's location. It then connects the user to the server, which in turn reduces the latency between the user and application 


