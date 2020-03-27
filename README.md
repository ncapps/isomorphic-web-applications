# Isomorphic Web Applications by Elyse Kolker Gordon

## Chapter 1. Introduction to Isomorphic Web Application Architecture
- *Server-rendered* apps handle each action the user takes by making a new request to the server
- *Single Page Applications (SPAs)* handle loading the content and responding to user interactions entirely in the browser
- *Isomorphic web apps* are a combination of the server-rendered and SPA approaches
- Make sure any libraries you include in an isomorphic app support running in both the server and browser environments
- *Initial load* is the first time the user interacts with your website
- Advantage of an isomorphic app architecture
  1. Simplified and improved SEO - bots and crawlers can read all the data on page load
  2. Performance gains in user-perceived performance
  3. Maintenance gains
  4. Improved accessibility because the user can view the app without JavaScript
- *Bootstrapping* an application means running the code required to get everything set up. This code is run once at initial load.
- [Google Page Speed Insights tool](https://developers.google.com/speed/pagespeed/insights/) measures page load performance
- [Lighthouse](https://developers.google.com/web/tools/lighthouse/) is a tool for improving the quality of web pages
- *Above-the-fold* refers to all the content that's in the viewable area of a user's screen when the app loads
- Server-rendered pages displays content as soon as the browser receives and renders the HTML. This fast load time is called *perceived performance*
- The *virtual* DOM is a representation of the browser DOM written with JavaScript
- React uses JavaScript to represent DOM nodes
- React provides a way to output the rendered DOM as a string (`ReactDOM.renderToString`). This string can be used to build a complete HTML page that's served from a server

**Summary**
- Isomorphic web apps provide improved perceived performance, simplified SEO, and developer benefits
- React's virtual DOM lets you render HTML on the server
- JavaScript can be used in both Node.js (server) and browser environments
- Redux helps you manage application state and easily serialize this state to be sent from server to browser

## [Code Samples provided by the author](https://github.com/isomorphic-dev-js)

## Attribution
[Isomorphic Web Applications by Elyse Kolker Gordon, May 2018, ISBN 9781617294396](https://www.manning.com/books/isomorphic-web-applications)