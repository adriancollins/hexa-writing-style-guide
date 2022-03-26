# README Guidelines
A README file is a plain text file that introduces and explains your project. Create it in the top level directory of your project.

## Goal
The goal of your README file is to help your reader do 4 tasks.

1. Identify your project.
2. Evaluate your project.
3. Understand how to use your project.
4. Engage with your project.

A README is not documentation. Keep it as short as possible. Try to treat it as an introduction to your project.


### 1. Identify your project
**Project name**

Give your project a simple name that describes it and distinguishes it from other projects. Additional information should be in your project's documentation.

*For example,*
```
hexa-hyperlink-checker
```


### 2. Evaluate your project
**Project description**

Tell your reader the goal of your project. Tell them what it can do and how it differs from similar projects

*For example,*
```
The hexa-hyperlink-checker is a command line tool that automatically checks hyperlinks in your markdown files.
This is similar to other hyperlink validation tools but this tool also identifies shortened URLs that can be problematic in Hexa.'
```

### 3. Understand how to use you project
**Prerequisites**

List the tools, including software versions, and access rights your reader needs to have before they can use your project. Add available links to tools and include information about required service tickets.

*For example,*
```
* Git
* Python 3.8.x
```


**Running the project**

Tell your reader how to run or use your project. Tell your reader what the expected outcome will be. This helps them to understand that it's working. A screenshot or animated GIF is useful here to orientate your reader.
Where appropriate, consider adding some test files to your project where your reader can test their own installation.

*For example,*

*Command*
```
  $ python hexa-hyperlink-checker test_markdown.md
```
*Result*
```
  $ line 43: bi.ty/34fdf7  shortened URLs are not allowed.
```

### 4. Engage with your project
Add more information about your project here such as links to the project website and documentation, guidelines for contributing, and details for project support.


## README template
Use this guide for your README. Change as you need.

```
# <project-title>

## What is this?
<this is your project description. Describe what it does and how it's different from something else.>

## Prerequisites
<* you need this>
<* and this>
<* and this>

## Running the project
<list of commands and descriptions you need to run the project once>

## Links
<project website>
<project documentation>

## Contributing
<Link to the project CONTRIBUTING.md file. See the [contributing guidelines](docs/contributingguidelines.md) for a sample guide on defining how someone can record issues or make changes.>

## Learning resources
< Use these recommended resources to get a better understanding of this project.>
<* Resource 1, *For example [Java Fundamentals](https://app.pluralsight.com/library/courses/java-fundamentals-core-platform/table-of-contents)*>
<* Resource 2 >
< More resources for the project are details in the [SUPPORT file](SUPPORT.md)>
< Access all recommended training and learning resources within Hexa at [Learning Resources](http://www.mountainminddesign.com/brand-central-website-case-study)>


## Community
<Outline at a high level how your team builds community. Provide more details in the `SUPPORT.md` file>
```

## Finally

**Test**

Test your README for technical accuracy (do the links and commands work?) and comprehension (does it make sense?). Ideally, ask a colleague to test your README. If this isn't possible, take a break and try to approach testing as a new reader.


**Maintain**

As your project grows so too should your README. Review and update your README regularly.
