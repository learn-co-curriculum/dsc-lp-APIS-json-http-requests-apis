---
title: 
layout: post
weight: 10
hidden: true
---

===


**Course**: DS   <br/>
**Mod**: Mod   2             <br/>
**Topic**:  JSON / API Requests  <br/>
**Amount of time**:  60 minutes  <br/>
**Author**: Sean Abu Wilson, + Forest Polchow   

Ported from the ds-lesson-starters repository [here](https://github.com/learn-co-curriculum/ds-lessons-starter/tree/master/lesson-plans-by-mod/Module-2/JSON_APIs_SW).


***

#### Lesson Summary:

This lesson is largely a lecture that rehashes two Learn CodeAlongs: [HTTP Request/Response Cycle - Codealong](https://github.com/learn-co-curriculum/dsc-http-request-response-codealong) and Using the [Yelp API - Codealong](https://github.com/learn-co-curriculum/dsc-using-yelp-api-codealong). The end of the lesson extends these by introducing pagination and asking students to review previous knowledge, performing some exploratory analysis on the retrieved data.

#### Topic:

API Requests

#### Learn.co material:

* [HTTP Request/Response Cycle - Codealong](https://github.com/learn-co-curriculum/dsc-http-request-response-codealong)
* [Yelp API - Codealong](https://github.com/learn-co-curriculum/dsc-using-yelp-api-codealong)

#### Prerequisite knowledge/ Prework:

Lists, dictionaries, Pandas and basic EDA.

#### Learning goals for this lesson:

• Navigate a JSON file
• Make API get requests
• Write Get request headers
• Parse an http response

#### Key Takeaways

* HTTP get requests will respond with an object that contains a status code AND content
* The content you are interested in will be stored under the `.json()`	method of the object.
* You can also send data to a HTTP endpoint with a post request
* JSON files are nested data structures similar to nested dictionaries and lists
* Be careful about API rate limits when making requests

#### Misconceptions / Notes


#### Materials
- Ipython notebook

#### Vocab / Concepts 

* HTTP Requests
* HTTP Status Codes: 200, 400, 404
* HTTP Get / Post Requests
* API
* Headers

#### Lesson Outline:

* Review of JSON structured Files (10-15 minutes)
* Introduction to HTTP Requests (5 min)
* Types of Requests (5 min)
* Navigating Response Objects (10 min)
* Writing an API Call (10 min)
* Pagination Exploration (10 min)
* EDA (10 min)
