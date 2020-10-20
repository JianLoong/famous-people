
![Logo](./logo/cover.png)

People API is a **static** and **crowd sourced** public RESTful API.

[![Netlify Status](https://img.shields.io/netlify/ca645974-c638-4ce7-8094-0dd7a9e59281.svg?style=square)](https://github.com/JianLoong/famous-people)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=square)](https://opensource.org/licenses/MIT)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=square)](https://github.com/JianLoong/famous-people/issues)
![CODE SIZE](https://img.shields.io/github/languages/code-size/JianLoong/famous-people?style=flat-square) 

# Features

- Easy to use RESTful API.
- Static API which can be cached via Content Deliver Networks.
- Information can be added to the API.

# Motivation

The objective of this project is to create a crowd sourced API where people can
query information about a person. Information can also be entered easily and the information can then be queried.

# Data Storage

- People API does not make use of a traditional form of database to store information.

- When information is submitted from the website, a bot will create a PR to the database. If this PR is accepted, the website will automatically be rebuild using **Hugo**.

- **Hugo** will automatically create the front end pages as well as the API end points.

- All information thus, are stored in the Github repository itself. 

# Status

Currently this project is still is in infant stages. Features and improvements will be added over time. There are no set milestones for now.

# Example

**GET** request

```bash
curl --location --request GET 'https://peopleapi.netlify.app/people/v1/person/07f11040-0d6c-11eb-a25a-a7ac8d04aef7/index.json'
```

would return

```json
{
  "data": {
    "_id": "07f11040-0d6c-11eb-a25a-a7ac8d04aef7",
    "name": "Donald Knuth",
    "description": "Father of Programming",
    "permalink": "//peopleapi.netlify.app/people/v1/person/07f11040-0d6c-11eb-a25a-a7ac8d04aef7/",
    "date": "2020-10-13 15:52:00.821 +0000 UTC",
    "content": "&lt;p&gt;Don....omitted for brevity"
  }
}
```

# Contributing

There are two ways to contribute to this public API. One way is to directly go
to the form and submit a information about a person.

# How to Contribute

Please look [here](https://github.com/JianLoong/famous-people/blob/main/CONTRIBUTING.md)

# Technology Stack

This site is build using

- Hugo
- Staticman
- Netlify

