**Just Write Click**
https://www.youtube.com/watch?v=Y2ak5o0IqLw

Technical writing with Continuous Integration and docs-as-code

Search this website
JustWriteClick
 
Contact
 
Books
 
Introducing Docs Like Code
You are here: Home / social media / Why use GitHub as a Content Management System?
December 17, 2015 by annegentle 2 Comments

Why use GitHub as a Content Management System?
Why use GitHub as a Content Management System?
GitHub is a website that gives a user interface to source control. The tagline on the site is “Social Coding,” and I find that phrase to be an excellent summary of why GitHub is so useful for collaborative documentation. When writing for developers, write with developers, and believe me, developers are using GitHub for writing and coding. Like many tools, git and GitHub were created by fire—through a pressing need in 2005 for high-throughput and efficient source control management for the Linux kernel.

GitHub is the web interface, and git is the command-line tool that you use to copy files locally and track them. It’s cross-platform, so it works on Windows, Mac, and Linux operating systems. The biggest difference between git and other source control systems is that it merges files with a best guess rather than a “lock and checkout” model. The best guess for merging is often accurate but does require human inspection when the changes are too close to tell. The non-linear branching model means that you can experiment with many changes but still get back to a known state.

Here’s a brief vocabulary list for GitHub.

A repository is a collection of stored code or source documentation. For example, openstack-manuals.
A branch is an indicator of divergence from base. For example, the stable/liberty branch of openstack-manuals.
A commit is a point-in-time snapshot of a repository with changes. For example, this typo commit.
A fork is both an action and an object: forking is when you copy a repository, and a fork is a copy of a repository.
An issue in GitHub is a way to report defects, tasks, or feature requests. For example, an install article issue.
An organization in GitHub is a collection of repositories. For example, Rackerlabs contains Rackspace repos.
A pull request is a comparison of edits to see if the reviewing team wants to accept those changes into the main repository. For example, this pull request for a Rackspace page on developer.rackspace.com.
GitHub has some offerings that cover a couple of different use cases. Private repositories on the public site are about $7/month as a subscription and let you mark a repository as private and only invite trusted collaborators. GitHub also has an enterprise offering where the entire website is hosted where you want it and branded with your domain name. With GitHub Enterprise, you can ensure only company employees can access the source and collaborate with each other. Look up more options and pricing information on https://github.com/pricing.

Why use GitHub instead of a traditional CMS for docs?
When you are collaborating with technical people on distributed projects, often they are already accustomed to a GitHub workflow. So applying that workflow to technical documentation related to the project is a natural fit. Also, since GitHub has flexible review processes and prioritizes continuous integration, applying those benefits to documentation reviews and builds gives you the benefit of content management while bridging to sharing knowledge with subject matter experts. GitHub is a great match for when developers are writing documentation in source control. GitHub works well when a project is so large or distributed that no one person can know enough to write the documentation for the project. While GitHub is often associated with source control, the collaborative aspects go well beyond the traditional source control and CMS models.

In OpenStack, we have documentation workflows that mimic our code collaboration. We post patches for people to review, we review each other’s patches (similar to a pull request on GitHub), and we have build and test automation for every doc patch. The idea is to use the collaboration available in the GitHub pull request workflow for docs as well as code. We’re all responsible for relevant and accurate documentation for about 25 OpenStack projects written in Python across 130 git repositories, so let’s work together.

I do get questions from writers who are getting started with these types of workflows, so I wanted to bring together some of the best practices we’ve found, and find more. Here are two articles that serve the purpose along with a slide deck from a presentation I gave this year.

Git and GitHub for open source documentation (article)
Continuous integration and delivery for documentation (article)


Git and GitHub for Documentation from Anne Gentle
Related

Now You Can Learn the Lingo of GitHub for Docs
Modernizing technical documentation
As a technical leader at Rackspace during a docs modernization effort, I want to respond to Tom Johnson's recent pointer to the developer docs site as an example of treating docs like code. Not just specifically for the "will it scale" questions, but for the questions I have fielded and…


Learn Git and GitHub Now with Three Doc Projects
Filed Under: social media, techpubs, tools, work, writing

Subscribe to Docs Like Code
Enter your email address to learn about docs like code in your glorious email inbox

First Name
 
Last Name
 
Email Address
 
Trackbacks
versiebeheer block – Sonny's Blog says:
April 8, 2016 at 11:54 am
[…] Een andere site die heeft uitgelegd waarom github als Content Management System (cms) te gebruiken => github cms. […]

Confluence: Agfa IITS Documentation Group says:
September 14, 2017 at 10:27 am
Generating static web sites via Jekyll on GitHub

Jekyll is a simple, blog-aware, static website gen

Leave a Reply
You must be logged in to post a comment.

Read More
Privacy Policy
About Anne Gentle, book author and developer experience expert
Books
Conversation and Community
Docs Like Code, a Book for Developers and Tech Writers
Speaker Profile
Contact
Just Write Click in your Inbox
Enter your email address to subscribe to Just Write Click and receive notifications of new posts by email.

Email Address
Email Address

Yes! Just Write Click in my Inbox

Recently on Just Write Click
How to Choose a GitHub Plan for Technical Writing?
How to Get Good Reviews with Docs-as-Code using GitHub
How to create a versioned docs site with Jekyll
Now You Can Learn the Lingo of GitHub for Docs
How to Modernize a Docs Site: Explore Three Static Site Generators
JustWriteClick
 
Contact
 
Books
 
Introducing Docs Like Code
Copyright © 2022 · WordPress · Log in
