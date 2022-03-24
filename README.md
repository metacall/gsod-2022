# Google Season of Docs 2022

## About MetaCall

[MetaCall](https://github.com/metacall) allows calling functions, methods or procedures between multiple programming languages. While working with different technologies and developers of different programming languages, the entire team's productivity worsens due to the lack of interoperability and communication between them. If the developers need two technologies written in different programming languages, for example, a C/C++ library called from NodeJS, and the team usually needs to port to one of the two languages or write a wrapper around them.

Maintaining a port of a library or the plumbing code is usually error-prone, time-consuming, and does not add any value to the final product. The main objective of MetaCall is to provide transparent interoperability in both ways, no matter what language you are using. This helps you feel like you are using a library written in the same language, but it may be written in C, NodeJS or whatever. We want polyglot applications to be written transparently and allow multiple developers to work on the same project using [different languages](https://github.com/metacall/core/blob/develop/docs/README.md#2-language-support).

MetaCall has a thriving community today on Discord, Matrix and Telegram, and we have supported contributors across multiple projects. We have participated in Google Summer of Code 2021 and will participate again in the summer of Code 2022. We aim to address the main shortcomings of embedding independent languages separately, and one of the most critical driving areas is good documentation. Through Google Season of Docs, we aim to redress this and drive a critical documentation infrastructure for all our projects in the coming time!

## State of MetaCall documentation

Currently, [MetaCall’s core](https://github.com/metacall/core) documentation is hosted on a simplistic Docsify website, which users can access over [core.metacall.io](https://core.metacall.io/#/). It displays community documentation curated by our contributors and a reference guide for the [MetaCall’s Core API](https://core.metacall.io/api/html/index.html). In the future, we have expanded our Core library further added more projects across infrastructure, tooling and our language support. The Core library has very high-level documentation over [markdown files](https://github.com/metacall/core/tree/develop/docs), which we have realized is insufficient to encompass all aspects of our documentation infrastructure and onboard new users and contributors!

Some of the critical areas that we have overall identified throughout reviewing MetaCall documentation are the following:

-   Lack of critical documentation around setting up various projects, including their build and environment configuration.  
-   Lack of training examples and case studies can help a user critically understand the scope of the Core library and its use-cases.
-   Lack of a central documentation website where all our collective docs can be hosted and referenced while providing a central point.
-   Lack of contributor documentation around making new loaders to support new languages in our Core library.
   
Through Google Season of Docs, we aim to work on identifying the correct solutions for these problems and building an infrastructure around them while creating the first version of our documentation. We have been using [Docsify](https://docsify.js.org/#/), [Doxygen](http://www.doxygen.nl/), [Sphinx](https://www.sphinx-doc.org/) and [plain Markdown](https://www.markdownguide.org/getting-started/) for our documentation efforts, but we would certainly like to pick one strong option as we advance!

## Project Idea: Building the documentation website for MetaCall

MetaCall has a large community of users and contributors, but no central point for documentation! It is often blocking for folks who are new to the community and have no fixed path of leveraging the community resources to get started on their user journey. Currently, reviewers and mentors help/guide contributors with such questions; however, we need a critical single-source-of-truth for all our documentation needs. This would ensure the branding for our Core library as a credible, open-source project and instill trust in our processes and workflows while we build our community!

The project scope involves developing a documentation website for the MetaCall using a modern static-site generator while writing credible and intuitive docs for the MetaCall projects. This project aims to address all the documentation needs for the community while ensuring that the contributors find it helpful to reference while they are working on the Core library and the other projects associated with it!

The goals associated with the project would be:

- Building a new documentation website for the MetaCall community:

  - Brainstorm and pick the right static site generator for the purpose and set a wireframe.
  - Collaborate with the mentors and volunteers in deciding upon a UI/UX workflow for the docs and implement it.
  - Publish the documentation website and triage the list of documentation pieces to be done on priority.

- Adding project-level documentation on the documentation website:

  - Pick up the projects that would ideally like to be documented in the first go by collaborating with the MetaCall mentors.
  - Migrate the existing documentation to the website while adding more context on build, setup and the user story.
  - Audit the documentation to ensure a consistent experience, which is currently fragmented and difficult to navigate.

- Develop community-focussed documentation for the website:

  - Brainstorm and plan contribution workflows for new contributors in the community.
  - Create content for our contribution guide to set up consistent contribution workflows.
  - Develop a funnel to track activity and user insights on the documentation website and the adoption ratio.

The mentors for this project are [Vicente Eduardo Ferrer Garcia](https://github.com/viferga) (MetaCall Core maintainer and GSoC admin) and [Harsh Mishra](http://github.com/harshcasper) (GSoC ‘21 contributor and GSoC ‘22 mentor).

## Project Idea: Developing tutorials, case studies and Core documentation

The central focal point in the MetaCall community is our Core library. The Core library facilitates cross-language function calls, and it allows us to extend our library further with new features! However, we don’t have enough documentation on interacting with Core and adding more features to it, like loaders (that are central for adding new language support). It would support our open-source contributors and the users who would like to understand how Core works underneath while replicating examples and case studies to adapt our library further.

The project scope involves collaborating with the mentors and volunteers to explore various use-cases tutorial topics to develop educational content to manage the rising interest in the MetaCall community. We also want to work on further improving the MetaCall core documentation by adding more credible docs on our loaders and internal architecture to make our functionality more accessible.

The goals associated with the project would be:

- Develop new tutorials for the MetaCall Core library:

  - Work with the mentors and volunteers to prioritize a list of tutorials that can be prepared alongside code examples.
  - Provide at least three beginner-friendly tutorials with code samples to use MetaCall Core for varying use-cases.
  - Design a content strategy to prepare new tutorials for the MetaCall Community to be further used for adopting new tutorials.

- Prepare documentation for the MetaCall Core:
  - Understand how new loaders are engineered in the Core library with a MetaCall mentor.
  - Develop documentation piece for new contributors to write a case study on writing new loaders for the MetaCall Core.
  - Build a reference guide for loaders to be extended as ports and define a contribution workflow across the entire effort.

- Write user-facing documentation for the MetaCall Core:

  - Develop new API documentation for the Core library and weed out outdated documentation.
  - Create new architecture diagrams for the Core library and coordinate its publication on the documentation website.
  - Migrate existing Core documentation to the documentation website after a technical audit.

The mentors for this project are [Vicente Eduardo Ferrer Garcia](https://github.com/viferga) (MetaCall Core maintainer and GSoC admin) and [Gil Arasa Verge](https://github.com/giarve) (MetaCall Core maintainer and GSoC admin).

## Measuring the project’s success

We will assess the success of this project on the following metrics:

-   Benchmark the success of the documentation by setting up Google Analytics and onboarding the first 100 users.
-   Migrate the documentation of at least five projects under the MetaCall Community to the documentation website.
-   Development of at least three new tutorials with code samples for users to try out MetaCall Core.
-   Triple the number of pull requests made to the MetaCall projects from 10 to 30 and double the number of contributors from 35 to 70.
-   Expand the adoption of API reference guide develop documentation and user guides by 50% with proper docs testing funnel.

## Skills required

We are looking for contributors with skills in the following:

-   Good skills in technical writing, including user-facing and developer-focussed documentation.   
-   Good skills in documentation tools, preferably in and around static site generators and documentation testing.    
-   Familiarity with programming languages like C++, Python and/or JavaScript along with working on external APIs and SDKs.  
-   Past experience in open-source communities and contributing to open-source projects.

## Project milestones

| Milestone                                                       | Date               |
| --------------------------------------------------------------- | ------------------ |
| Releasing the first version of documentation website            | May 22, 2022       |
| Publishing the first set of tutorials on Core library           | June 20, 2022      |
| Adding project-level documentation for MetaCall Community       | July 26, 2022      |
| Developing MetaCall Core documentation and API reference guides | September 10, 2022 |
| Build community guides for contribution to MetaCall projects    | October 23, 2022   |
| Building GSoD case-study and testing the project impact         | November 15, 2022  |

## Project budget

| Budget Item        | Amount  | Notes          |
| ------------------ | ------- | -------------- |
| Technical Writers  | $10,000 | 2 x $5000 each |
| Volunteers/Mentors | $1,500  | 3 x $500 each  |
| Schwags/T-Shirts   | $150    | 5 x $30 each   |

## Get in touch

First of all, if you have not done that yet, read the [technical writer guide](https://developers.google.com/season-of-docs/docs/tech-writer-guide), which will allow you to understand all this process and how the program works overall. Refer to its left side menu to quickly access sections that may interest you the most, although we recommend reading everything.

Next, get in touch with the mentors and discuss the project idea. This is a required step, and you must understand the basics about the idea you prefer above on the list. A few things that we might ask you to understand are:  

-   You're committing to a project, and we may ask you to publish your weekly progress on it publicly.    
-   It's the first year MetaCall is joining the GSoD program, and we will ask you to give feedback on our mentorship and management continuously.   
-   You wholeheartedly agree with the [code of conduct](https://github.com/metacall/core/blob/develop/.github/CODE_OF_CONDUCT.md).
-   You must tell us if there's any proposed project idea that you don't think would fit the timeline or could be boring (yes, we're asking for feedback).

We recommend you to follow Google's guide to [creating a statement of interest](https://developers.google.com/season-of-docs/docs/tech-writer-statement) as we won't be too harsh on the format. You can send the proposal link in any readable format you wish: Google Docs, plain text, in Markdown... and preferably hosted online, accessible with a standard browser without downloading anything.

You can also ask for a review anytime from the community or mentors before the application deadline. It's much easier to get feedback early than to wait for the last moment.

## Additional notes

[metacall.io](http://metacall.io) currently refers to a commercial FaaS (run by the organization admins) and that's why all links refer to a Github organization and not a website. However, all the communication channels stated in the application are from the open source organization and in the future metacall.io may host the open source project website (moving the FaaS to another domain, and rebranding) to avoid generating any type of confusions.

## Find Us

The three chats are bridged by Matrix (messages sent from one can be seen from all).

Telegram:
<a href="https://t.me/joinchat/BMSVbBatp0Vi4s5l4VgUgg" alt="Telegram"><img src="https://img.shields.io/static/v1?label=metacall&message=join&color=blue&logo=telegram&style=flat" /></a>

Discord: 
  <a href="https://discord.gg/upwP4mwJWa" alt="Discord"><img src="https://img.shields.io/discord/781987805974757426?label=discord&style=flat" /></a>

Matrix:
  <a href="https://matrix.to/#/#metacall:matrix.org" alt="Matrix"><img src="https://img.shields.io/matrix/metacall:matrix.org?label=matrix&style=flat" /></a>