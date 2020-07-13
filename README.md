

<img src="https://golayer.io/_next/static/images/og-image-main-1dba5191d93673f0410cf1502627299b.png" width=400>


# Layer Backend Engineer Challenge

## Background

There is a publishing house, which publishes the "Layer Weekly" magazine. The management of the publishing house all of a sudden decided to switch their employees to fully remote positions. In the process of establishing how the company would handle it, the management came up with a solution to exchange articles by e-mail. Unfortunately, the process was long and error-prone, so the Editor in Chief decided that they need a collaboration tool to ease the process of drafting and publishing articles. "IT to the rescue"! — our story begins here.

## User Stories

1. As an editor in chief, I add a list of topics for the new edition of a magazine.
2. As a journalist, I submit a draft article for publishing to a given topic
3. As a copywriter, I suggest changes to the draft article I'm assigned to
4. As a journalist, I respond to suggestions by making the suggested changes
5. As a copywriter, I resolve suggestions that the journalist applied
6. As a journalist, I can publish the article after all suggestions are resolved

### Details

- An article is a simple text with a title and some headings
- The draft article:
    - needs to have title and content
    - can be connected to multiple topics
- Journalists cannot change each other's drafts
- Copywriters can only suggest changes to article they were assigned to.
- Suggested changes can be considered as comments to the whole article. They should be non-empty chunks of text.
- Once the article is published, suggestions are no longer allowed.

## Task

In your preferred language write an application that covers 3 of the user stories from above. You can choose freely which ones you want to implement.

## **Evaluation criteria**

The most important part for us is the domain model. We appreciate DDD solutions. Technology stack is up to you but please remember that it's not the technicalities that impress us. 

Consider the challenge as you would do it at work, with all best practices you know. Feel free to use any input for the domain logic you feel is needed. API, CLI, Acceptance tests etc.

### What we judge

- Your modelling skills. Is it possible to understand the problem from the code?
- You follow best practices appropriate to your language of choice
- Code is organised, clean and readable.
- Code is maintainable.

### What is irrelevant

- We don't judge GUI so please do not focus on that.
- Your implementation can stop at application level. Do not focus on the REST or GraphQL controllers.
- Please do not focus on persistence or database. If you wish it also can be skipped altogether.

## Timeline

- As a rule, you shouldn't spend more than 6-7 hours on the taks in total.
- **Tell us about the date** when you will send in the result by replying to [careers@golayer.io](mailto:careers@golayer.io). We don't mind if you take more time - it will not affect the evaluation.

## Deliverables

- **Create a private repository** on GitHub (they are free). When you finish the challenge, invite `bez4pieci` as a collaborator to the repository you created and send a notification e-mail to [careers@golayer.io](mailto:careers@golayer.io) (reply to the email where you received the code challenge).
- Write your solution in code, and use multiple commits.
- It is not required but if you like you can attach all documents, mockups, or diagrams which help you develop the code.
- We will appreciate additional information about
    - how you gathered all required information for architecting the domain model
    - how you came up with assumptions
