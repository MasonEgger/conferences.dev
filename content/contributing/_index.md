---
title: "Conferences"
---


You can contribute a conference to conferences.dev in one of two ways

## Creating a Copy
Perhaps the easiest way to contribute would be to make a copy of an existing
conference and replace all of the front matter with the appropriate information. 
You can use an existing conference (`content/conferences/pytexas.md` is a good
one with all the appropriate front matter) or `archetypes/conferences.md`. 
This is the base template of every conference page.

## Using Hugo

* [Install Hugo](https://gohugo.io/getting-started/installing/) v.0.91.2 or later
* Fork the code from [github](https://github.com/Conferences-Dev/Conferences-Dev.github.io)
* Run the command `hugo new conferences/<CONFERENCE_NAME>.md
    * This will create a new conference page at `content/conferences/<CONFERENCE_NAME>.md`
* Fill in the front matter as instructed by the comments and add a description of
the conference.
* Test your changes by running `hugo server`

## PR Process
* Create a new branch, preferably named the name of the conference your adding. If you're
adding more than one then give it a generic name.
* Check in your branch.
* Submit a pull request back upstream.
* A maintainer will review your PR and give feedback if any is needed. Once
the maintainer has merged the PR it will be built into the live site.

## Style and Guidelines

* Do not include any date information within the conference title