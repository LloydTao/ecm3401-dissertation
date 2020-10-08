---
title: Project Statement and Plan
description: ''
position: 210
category: 'Work'
---

## Project Statement

My proposal is to build a feature-complete web platform for trading and investing in stocks and shares. 

By targeting the young adult demographic (aged 18 to 25), the aim is to provide the end-user with a streamlined investment portal, and in doing so, abstract the daunting parts of capital investment. 

## Challenge

In order to judge the technical and conceptual scope of the task, we can break it down into its two core parts.

The software solution will be composed of a back-end data lake and a front-end web application.

### Data lake

The role of a back-end web server is to handle requests, application logic and data. Due to the task's complex data requirements, we require an advanced data infrastructure solution.

A data lake is cloud infrastructure designed to ingest and process real-time streams of data, with the goal of a unified data access layer.

Its benefit is that it provides centralised repository for data at any scale, which can cater for both raw and processed datasets. Inputs will include real-time stock market data and in-app events.

By unifying the data access layer, all user interaction is handled in one place. 

Possible use cases are an internal compliance team running security checks, a research team implementing machine learning for product recommendations, and an end-user attempting to register an account and purchase stocks.

The challenge will first be to design a data lake that can fulfil all application requirements. Then, it will be to implement it as a highly-available, cost-efficient, fault-tolerant, and scalable distributed system on the cloud.

### Web application

The web application is an online interactive graphical interface, designed for users to view and interact with the platform.

Its purpose is to hook into the data lake back-end in order to facilitate some functionality for the end-user. This will include registering an account, signing in, viewing live stock market data, and purchasing and selling stocks and other securities.

For communication between the systems, there needs to be some general-purpose server-side API. This will serve as an intermediary to allow the applications to talk to each other.

Overall, this side of the project encompasses UI (user interface) and UX (user experience) design, both in concept and in implementation.

## Value

For the end-user, the goal is to influence social mobility and bridge the generational wealth gap. 

According to investing app *Stash*, nearly 80 percent of millennials do not hold capital investments. This is likely due to a fear of risk, a lack of financial education, and unclear solutions in how to do so. My application will attempt to solve these issues.

For the reader of the paper, I hope to provide insight into a few areas. It will explore how financial applications can be developed for the younger members of our society, where money needs to be handled carefully.

Additionally, it will provide a documented approach into how data lake architecture can be specified, designed, implemented and tested will be highly-valuable. 

Solving big data analytics with a data lake is a relatively new approach, and since specific use-cases tend to only be tackled in commercial applications, there's not a lot of published material out there.

