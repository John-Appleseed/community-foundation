## Goal

Be the **hub** of **Foundation resources** to help **Web Designers** produce **faster** and **better** **websites**.

---


- [ ] Message Board to share resources
```cucumber
Feature: Message Board
In order share CSS frameworks examples, links, and downloads
As a Web Designer
I gain information and UI template files to design better faster with the Foundation framework

Values: Share
- Advice
- Questions
- Answers
- Links
- Images - png, psd, jpeg
- CSS Code
- HTML Code
- Video - Flux Video


Risks:
- IE lacks support for websockets. Use Javascript polling


Units:
- File Data storage - for the message file uploads
- Message storage - Postgres or MonogoDB - to store the chat log


Milestone: 1 - Community Construction


Scenario: Sharing a PSD UI Foundation Kitchen Sink file
	Given I am logged in Community Foundation
	And the browser supports gzip compression of psd docs
	When I Drag and Drop or press the Upload button
	Then a message is posted on the board with an File Image and filename description. iMessage style
```


- [ ] Design the Community Kitchen Sink of UI elements
- [ ] Code Guard to refresh web browser when css files are changed within the app folder



# [Foundation](http://foundation.zurb.com)

[![Build Status](https://travis-ci.org/zurb/foundation.svg)](https://travis-ci.org/zurb/foundation)


Foundation is the most advanced responsive front-end framework in the world. You can quickly prototype and build sites or apps that work on any kind of device with Foundation, which includes layout constructs (like a fully responsive grid), elements and best practices.

To get started, check out <http://foundation.zurb.com/docs>


## Quickstart

To get going with Foundation you can:

  * [Download the latest release](http://foundation.zurb.com/cdn/releases/foundation-latest.zip)
  * [Install with Bower](http://bower.io): `bower install zurb/bower-foundation`

## Documentation

Foundation uses [Assemble.io](http://assemble.io) and [Grunt](http://gruntjs.com/) to generate its [documentation pages](http://foundation.zurb.com/docs). Documentation can also be run from your local computer:

### View documentation locally

You'll want to clone the Foundation repo first and install all the dependencies. You can do this using the following commands:

```
git clone git@github.com:zurb/foundation.git
cd foundation
npm install -g grunt-cli bower
npm install
bower install
```

Then just run `grunt build` and the documentation will be compiled:

```
foundation/
├── dist/
│   └── ...
├────── docs/
│       └── ...
```

Copyright (c) 2014 ZURB, inc.
