---
title: Jeopardy! Web Application
summary: A web application built with Vuejs and Nodejs that allows users to interact with more than 380,000 Jeopardy! questions dated back to 1986.
tags:
  - Web Development

date: "2020-12-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption:
  focal_point: Smart

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: "https://github.com/dattnguyen/jeopardy_web_application"
url_pdf: ""
url_slides: "https://docs.google.com/presentation/d/10IXIkFkP-CupW_dLJti5182DNRlJbQHo/edit#slide=id.p1"
url_video: ""
# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

Our application is modeled after the show, Jeopardy!, which features a quiz competition in which contestants are presented with general knowledge clues in the form of answers and must phrase their responses in the form of questions. The questions can come from any category and in order to win, contestants must rack up the most amount of money. Having been aired for decades, this immensely popular show has gained worldwide recognition and continues to be an entertaining show for everyone to enjoy.

Our application serves two main purposes. Primarily, our application is meant to be a fun trivia site for fans who want an interactive Jeopardy! experience. Additionally, our application can also be used by prospective contestants who want to sharpen their trivia skills and gain insights into the patterns of questions and answers before appearing on the show.

The motivation behind this idea comes from the fact that we are Jeopardy! fans and there is currently no comprehensive site where fans can play the games as well as view statistics about the show. In recent history, some Jeopardy! winners have successfully used computer models in order to effectively and efficiently train for their appearances on the show, but for contestants without programming backgrounds, this type of training is not feasible. With our application, any prospective contestant is able to leverage analytical insights in order to best prepare for the show.

The underlying technologies we used to create our application are as follows:

- Python - Web Scraping: We scraped two of our datasets relating to contestants from J! Archive using Python. The first dataset we scraped contained data about winners and contestants per episode. The second dataset contained data about each contestant themselves, unrelated to the show.
- Amazon Warehouse Services (AWS) Relational Database Services (RDS): Our database is maintained and hosted on AWS.
- Oracle SQL Developer: After establishing our database, we connected it to Oracle SQL Developer, which we used to load and query our data. Our application is also directly connected to this.
- Tableau: We integrated Tableau in order to create data visualizations that better communicated certain statistics on our Contestants and Questions pages.
- Node.js: We used Node.js as the JavaScript runtime environment that executes JavaScript code outside a web browser. It allows us to run scripts server-side to produce dynamic web page content before the page is sent to the user’s web browser.
- Vue.js: Vue is a model-view, front-end JavaScript framework. We used Vue to build the user interfaces for our trivia site.

## Installation Instruction

- Server:

  - Our server connects to Oracle. In order to run the application, please make sure you have Oracle Instant Client and SDK installed.
  - Once it's installed, update the path to the client in the routes.js file at the very top within oracledb.initOracleClient({ libDir: '' })
  - Use "npm start" to run server from within server folder (after npm install)

- Client:

  - Use "npm run serve -- --port 3000" to run client from within client folder(after npm install)
  - If this fails, first delete the "node_modules" folder in the client folder and run npm i. Then try again.

## Preview

{{< figure library="true" src="play.png" title="A Preview of the Play Page" >}}

We hope you enjoy it!
