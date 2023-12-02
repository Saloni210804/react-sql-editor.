# REACT SQL Editor

## Description

Create, design and implement a web-based application capable of running SQL queries and displaying the results of said query. The application must include a space which accepts SQL queries in the form of user inputs, then runs the given query, and displays the result within the application..

This is a REACT SQL Editor built using ReactJs and TailwindCSS.

## Live Demo

<a href="https://github.com/sambitos23/react-sql-editor" target="blank">
<img src="https://img.shields.io/website?url=https://www.codingspace.codes&logo=github&style=flat-square" />
</a>

Try out the website : [REACT SQL Editor](https://react-sql-editor-beta.vercel.app/)

## Tech Stack

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

##  Dependencies

- **_react-ace_**
- **_react-csv_**
- **_react-hot-toast_**
- **_tailwind-scrollbar-hide_**

## Features

:white_check_mark: Users can get data of any of the predefined SQL queries on the left Sidebar menu.\
:white_check_mark: Users can view all the table column on Right Sidebar menu.\
:white_check_mark: Users can check all the table value on clicking Table name of Right Sidebar menu.\
:white_check_mark: Users can download the data in CSV Format in just one click.\
:white_check_mark: Users can see query runtime in milliseconds(ms).

##  Predefined SQL Queries

- `select * from customers;`
- `select * from suppliers;`
- `select * from products;`
- `select contact_name, address,city,postal_code, country from customers limit 18;`

## Page Load Time

Page Load time of this website in desktop is in the range of 0.4 s to 0.6s.
we can check code spnappyness GTmetrix Grade.

![GTmetrix Grade Report][snapyness]--- (https://github.com/Saloni210804/react-sql-editor./assets/121386095/6bdd8a0c-52e8-459e-bafa-9574c569e605)
GTmetrix Grade - A, Performance 100%, Structure-99%, Web Vitals: LCP:266ms, TBT 0ms, CLS 0.

### [web.dev Report](https://pagespeed.web.dev/)

Laptop performance view

![web.dev Report]-----<img width="549" alt="performance" src="https://github.com/Saloni210804/react-sql-editor./assets/121386095/a03f22cb-e8a2-4c38-8957-04020ac8d738">
100% performance, first contentful paint- 0.2s, speed index- 0.9s, Largest Contentful Paint-0.5s, Time to interactive- 0.5s, Total blocking time- 0ms, cumulative layout shift - 0.

Mobile performance view

![web.dev Report]------
<img width="510" alt="mobileperformance" src="https://github.com/Saloni210804/react-sql-editor./assets/121386095/505298f7-9e56-44b5-ac20-0ecb03c38d49">
98% performance, first contentful paint- 0.8s, speed index- 1.7s, Largest Contentful Paint-2.2s, Time to interactive- 2.2s, Total blocking time- 120ms, cumulative layout shift - 0.
Mobile performance view

## Steps I took to optimize the page load time

- Used Lighthouse DevTools Extension to find the performance issues and fix them using their actionable suggestion.
- Used vercel to deploy this website to leverage its Vercel Edge Network compression that results in the better performance.

## Available Scripts

In the project directory, you can run:

### `npm install`

To install all the packages in package.json. This will install all the dependencies and devDependencies.

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

##  Project Output

![Homepage]-----<img width="960" alt="main_project" src="https://github.com/Saloni210804/react-sql-editor./assets/121386095/c99e0d50-37b3-4906-b61b-c280b5f7ae67">

# react-sql-editor
This is a REACT SQL Editor built using ReactJs and TailwindCSS.
# react-sql-editor.
This is a REACT SQL Editor built using ReactJs and TailwindCSS.
