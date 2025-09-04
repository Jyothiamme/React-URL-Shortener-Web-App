# React-URL-Shortener-Web-App
AffordMed 1st round
# Project Overview 
In this section, we'll provide an overview of the URL Shortener project. We'll discuss its main features, the technologies we'll be using, and the expected outcome of the application. Let's dive in!

# Main Features
Input form to submit URLs for shortening

API integration to generate shortened URLs

Display of the shortened URL to the user

URL history management with local storage

Copy-to-clipboard functionality for easy sharing

# Technologies Used 
To build our URL Shortener application, we'll be utilizing the following technologies and tools:

React: A popular JavaScript library for building user interfaces

Axios: A promise-based HTTP client for making API requests

Bitly API: A URL shortening service that we'll use to generate shortened URLs

React-toastify: A tool for displaying user-friendly notifications.

# What I Learned
During the development of this URL Shortener application, I gained valuable insights and learned several key concepts and techniques. Here are some of the main takeaways:

1.React Hooks: I deepened my understanding of React Hooks, such as useState and useEffect, which allowed me to manage the component state and handle side effects effectively. By utilizing useState, I was able to store and update the input form values and the shortened URL. The effect hook enabled me to fetch data from the Bitly API and handle the URL history persistence.

2.API Integration: Integrating external APIs in a React application was a crucial aspect of this project. I successfully integrated the Bitly API, which provided the URL shortening functionality. This experience taught me how to make HTTP requests, handle API responses, and extract relevant data to generate shortened URLs dynamically.

3.LocalStorage: To provide a seamless user experience and enable persistence, I leveraged the localStorage object in the browser. This allowed me to store the URL history locally, ensuring that it remained intact even if the user refreshed the page or closed the browser.

4.Copy-to-Clipboard Functionality: I implemented a feature that enables users to copy the shortened URL to their clipboard with a single click. By using the document.execCommand('copy') method, I facilitated an intuitive and convenient way for users to share shortened URLs. 

5.CSS Styling: I enhanced the user interface of the URL Shortener application by applying custom CSS styles. Through CSS modules and inline styles, I achieved a visually appealing and responsive design that adapts smoothly across different devices. This experience improved my proficiency in CSS and responsive web design. 

6.Validation and User Feedback: Handling user input and providing meaningful feedback were essential aspects of the application. I implemented form validation to ensure that users enter valid URLs and displayed toast notifications using Toastify to inform them about the success of URL shortening or any errors that occurred. This enhanced the user experience and helped maintain data integrity. 

Overall, this project provided me with hands-on experience in React development, API integration, state management, local storage usage, copy-to-clipboard functionality, and CSS styling. Through overcoming challenges and applying these techniques, I further solidified my skills as a front-end developer and expanded my knowledge of web application development.
Thanks for sticking with me through all the setup and planning! Based on your project requirements, here's a simulated output of what your React URL Shortener Web App might look like when it's up and running. This includes a visual mockup and a description of the result you'd expect from your deployed app.


# Expected Functional Output
Here’s what your app will do:
- Accept long URLs and generate short ones using a public API or mock logic
- Store mappings in localStorage or Firebase Firestore
- Display a list of shortened URLs with copy/delete options
- Redirect users when they visit a short URL
- Show click analytics (if implemented)
- Authenticate users (if bonus features are added)
- Look clean and responsive across devices

# Deployment Results
https://your-url-shortener.netlify.app
https://github.com/your-username/url-shortener
# with a README that includes:
- Setup instructions
- Feature list
- Tech stack

