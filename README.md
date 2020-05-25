# 01 HTML CSS Git: Code Refactor

One of the most common tasks for front-end and junior developers is to take existing code and refactor it to either meet a certain set of standards or implement a new technology. Web accessibility is an increasingly important consideration for businesses, ensuring that people with disabilities or socio-economic restrictions have access to their website, and helping them avoid litigation.

Your task is to refactor an existing webpage to make it accessible. An important rule to follow when working with someone else's code is the Scout Rule:

> Always leave the code you are editing a little cleaner than you found it.

To impress clients, you should always go the extra mile and improve their codebase for long term sustainability. Ensure that all links are functioning correctly and clean up the CSS to make it more efficient, consolidating CSS selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page.

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
    clb:    change existing div tags to semantic elements (quincy will provide references)
    clb:    shouldn't have to change css since it's using classes and not updating divs
    clb:    website should render exactly the same as it does without semantic tags
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
    clb:    he said we don't have to do this?  not sure what this means - find out
    qi:     There is css that is repeated for different elements on the page, 
            see if you can use html classes to reduce the amount of duplicate css you have to write out
WHEN I view the image elements
THEN I find accessible alt attributes
    clb:    add alt attributes to images (done)
WHEN I view the heading attributes
THEN they fall in sequential order
    clb:    ignore for now - quincy will let us know, if not - follow up!
    qi:     safe to ignore
WHEN I view the title element
THEN I find a concise, descriptive title
    clb:    update the title of the website (done)
```

## Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository. Give the repository a unique name and include a README describing the project.

- - -
© 2019 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.


##  Revisions

I added comments to the index.html file to highlight my changes.  In a real-life scenario, I would eventually
remove this comments after internal review.

I also updated the style.css by combining several common classes as well as updating a div class to nav.
