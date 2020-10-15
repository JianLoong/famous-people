
# People API

People API is a crowd sourced public RESTful API.

[![Netlify Status](https://img.shields.io/netlify/ca645974-c638-4ce7-8094-0dd7a9e59281.svg?style=square)](https://github.com/JianLoong/famous-people)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=square)](https://opensource.org/licenses/MIT)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=square)](https://github.com/JianLoong/famous-people/issues)
![CODE SIZE](https://img.shields.io/github/languages/code-size/JianLoong/famous-people?style=flat-square) 


# Status

Currently this project is still is in infant stages.

However, the core concept of it is there. Suggestions for improvement are always good to hear.

# Example of RESTful Request

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

# Motivation

The objective of this project is to create a crowd sourced API where people can
query information about a person. Information can also be entered easily and the information can then be queried.

# Flow

Whenever a user contributes data via the front page done via the contribute page, it will send a PR to this repository. This is all automated.

When this PR is merged, it will re-create the needed pages which are statically generated for the REST API to work.

# Contributing

There are two ways to contribute to this public API. One way is to directly go
to the form and submit a information about a person.

# How to Contribute

Please look [here](https://github.com/JianLoong/famous-people/blob/main/CONTRIBUTING.md)

# Technology Stack

This site is build using

- Hugo
- Staticman

This site is actually a static site. There is no database present. All information are stored as markdown files.

