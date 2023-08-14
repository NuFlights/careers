# Pythonista

We would like to hear from you if you are passionate about your Python skills, and making a difference in a growing tech startup.
* Make sure you read [General Traits & Responsibilities](https://github.com/NuFlights/careers#general-traits--responsibilities) before you proceed

## How to apply

See: https://github.com/NuFlights/careers#how-to-apply


## Salary Range

* Our offers are competetive in the market, depending on your experience and skillset.

## Responsibilities

* You will have to build GraphQL APIs, and sometimes maintain and enhance our GraphQL frameworks.
* You are responsible for deploying your code, developing CI/CD pipelines and maintaining them.
* You may be required to build the product modules from ground up.
* You will have to implement new features with quality, and support them.
* Every day, you will have to adress bugs (atleast the critical/medium ones) before starting a new feature.
* Contiously optimize the parts of code that you feel can be written better
* In senior roles, monitor, research and suggest frameworks that improve team productivity and quality.


## Requirements

* See our `Tech Stack` below. You must be comfortable with at-least the *essentials* of the stack.
* Should have at-least 3 years experience in building backend / web applications (any scripting language / framework)
  * At least 2 of those years should be using Django (Or a comparable python framework).
  * The number of years may not matter if you can demonstrate your skills.
* Strong HTML; Proficient in JavaScript & CSS - preferrably basic React-skills.
* Exposure to Celery
* Good understanding of the Python development environment and use of developer support tools for quality and efficiency.
* Skills to containarise and deploy production and non-production servers.
* Good AWS fundamentals, with the ability to design right-sized and secure applications.
* Good understanding of JSON and XML messages and schemas, and exposure to using them in Python applications.

## Nice to have (Optional - but, these are huge plus)
* Basic understanding of GraphQL gateways, best practises and methods like schema stiching. See https://the-guild.dev/.
* Basic understanding of setting up and using local environments for cloud services.
* Basic understanding of setting up CI/CD pipelines using AWS services - ideally an AWS Foundations certificate
* Basic grasp on client-side Typescript (or Javascript)
* Exposure to other frontend frameworks like Angular, Backbone, Ember 
* SASS / LESS Experience is huge plus
* Go Lang / Elixir / Rust - atleast at a hobby level.


## Tech Stack
Our choice of technology tooling is growing, but we focus on the foundations below.

### Essentials
You should have a strong understanding of the following:

* [Python](https://developers.google.com/edu/python/)
* [Django](https://docs.djangoproject.com/en/3.0/intro/install/)
* [GraphQL](https://www.edx.org/course/exploring-graphql-a-query-language-for-apis)
* [Graphene](https://docs.graphene-python.org/projects/django/en/latest/tutorial-plain/)
  * Or [Strawberry Rocks](https://strawberry.rocks/)
* [Celery](https://docs.celeryq.dev/en/stable/)
* [PostgreSQL](https://www.postgresql.org/)
* [Docker](https://docs.docker.com/develop/)

## Assignments
You must complete the first assignment below. If you can complete the second assignment, it will be a huge plus.

### Assignment 1
Using the tech stack above (a must to demonstrate the choices you make), build a simple blog API service. It should expose a GraphQL endpoint to do the folloing things:
 
1. Implement a `createPost()` mutation which will create a `Post` (a blogpost object) with attributes {`title`, `description`, `publish_date`, `author` (just a name as TextField)}
2. Implement a `updatePost($id)` mutation which will update a `Post` attributes by `$id`
3. Implement a `createComment()` mutation which will create a `Comment` object with attributes {`post` (the blogpost object), `text`, `author` (just the name as a TextField)}
4. Implement a `deleteComment($id)` mutation to delete the given `Comment` by its ID.
5. Implement a `posts()` query to list all the posts
6. Implement a `post($id)` query to get details of a post and all its comments

Please push the assignment to a private github repo and add [@rs-ds](https://github.com/rs-ds)) as a collaborator to your private repo.

### Assignment 2
Using the tech stack above (a must to demonstrate the choices you make), build a simple GraphQL query method, which exposes data from the XML message mentioned below.
1. The XML source message follow [`OrderViewRS.xsd`](https://github.com/NuFlights/careers/blob/main/resources/xml-schema/OrderViewRS.xsd) from the [XML schema here](https://github.com/NuFlights/careers/tree/main/resources/xml-schema). 
   * You may generate a sample with random data
2. Implement a GraphQL query that allows querying values from any selected set of elements (if possible attributes as well) from the sample XML.

Please push the assignment to a PRIVATE (do make sure it's private) github repo and add [@rs-ds](https://github.com/rs-ds)) as a collaborator to this private repo.