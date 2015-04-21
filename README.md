# mariecurie-interview-scenarios

Usage: This repository and scenario is designed as a way to assess team and skill fit for a backend C# developer within the Marie Curie digital development team.

## Task
We would like you to demonstrate your development skills by delivering a single page web site based on a set of requirements that match the way we deliver solutions within our team.

* Please timebox your work on this. We don't expect this task should take longer than **2 hours**.
* You will need a **GitHub account** to clone this (mariecurie-interview-scenarios) repository
* Please submit your solution in the form of a **pull-request**

During the face-to-face interview we would like to discuss your solution and your approach. We will expect you to demonstrate how the acceptance criteria have been met and also any challenges you faced during development.

If you have any questions, please get in touch.

*Good luck :)*

## Background
The Marie Curie Caring Services department wish to better promote their Helper service on the charity's website.

The Helper Service matches trained volunteers with people living with a terminal illness and provides support to them or their families. Support is provided free of charge and is available to people aged 18 or over with any terminal illness, and their families

The Website Scrum team Product Owner and Business Analyst have agreed with the Caring Services team that a page will be developed for the website that will list out available Helper Services; show how they can be contacted and dynamically highlight if and when they can be contacted.

## User Story
The following user story and acceptance criteria was created and will be used by the team to design and validate their work.

As a website user who needs help and support
I want to be able to find Helper Service
so that I know what support is available to me and how to contact them 

**Background: GIVEN I am on the Marie Curie website**
 
**WHEN I view the Helper Service page**

**AC1: Display**

THEN I want to see a list that contains all Marie Curie Helper Services

**AC2: Detail**

THEN each Helper Service list item will have the following properties: Title - linked to a page (https://www.mariecurie.org.uk/help/helper-volunteers), Description, Telephone number and a currently open / closed status

**AC3: Dynamic status**

THEN I want to see whether the helpline is OPEN or CLOSED with the label copy as per below

OPEN - OPEN TODAY UNTIL `{closing time}`

CLOSED - REOPENS `{day}` at `{opening time}`

**AC4: Visual** 

THEN the Helper Service list item displays a clear visual representation of whether it is the service is open or closed

*Note: Full details of this visual representation required is given in the wireframe / annotations*

**AC5: Telephone**

THEN when I am using a mobile device, I should be able to tap the number to call the number.

## Technical Brief

### Integration
The Helper Service information is mastered in a back office CRM system and made available via a Nuget package containing a C# library. A fellow developer has already included the Nuget package in the repository for you. 

### User interface
Marie Curie use a modified Bootstrap theme for HTML based user interfaces. The theme uses a responsive 12 column grid. A basic layout page has already been built by the front end developer and is included in the source code repository.

A full description and style guide for our front end interfaces is available in our Brand Lab.

[http://mariecurieorguk.azurewebsites.net](http://mariecurieorguk.azurewebsites.net)

Additional HTML modules necessary for the solution have been pre-built by the front end developer and can be downloaded from the pattern library in the Brand Lab. These elements are called 'panels' within the pattern library

Both the layout page and additional modules are built against the same style sheet version.

--




