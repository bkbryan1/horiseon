# Coding Challenge 1: B. Bryan
Located in this file are the steps taken to complete the first coding challenge. Listed below is not only the overall requirements ([User Story](#user-story) and [Acceptance Criteria](#acceptance-criteria)) but also a breakdown of each coding lesson in the module to ensure maximum fulfillment of the [Acceptance Criteria](#acceptance-criteria).

## Due Date: `Sunday, Feburary 7, 2022`

## Challenge Mockup
![Mockup image](./assets/images/01-html-css-git-homework-demo.png)

## User story
Listed below is the "User Story" provided by the assignment:
AS A marketing agency<br>
`I WANT` a codebase that follows accessibility standards
`SO THAT` our own site is optimized for search engines

## Acceptance Criteria
Listed below are the criteria provided by the assignment:
GIVEN a webpage meets accessibility standards<br>
`WHEN I` view the source code<br>
`THEN I` find semantic HTML elements<br>
`WHEN I` view the structure of the HTML elements<br>
`THEN I` find that the elements follow a logical structure, independent of styling and positioning<br>
`WHEN I` view the image elements<br>
`THEN I` find accessible alt attributes<br>
`WHEN I` view the heading attributes<br>
`THEN they` fall in sequential order<br>
`WHEN I` view the title element<br>
`THEN I` find a concise, descriptive title

# Checklist of Submission Factors
Listed below are the items completed in this assignment:
* Clone the Starter Code.
* Refactor the code to meet the Acceptance Criteria.
* Ensure Files meet the full list of grading requirements.
* Review the [Lesson Topic Instructions](#lesson-topic-instructions) section below for a breakdown of the additional factors that were reviewed prior to submission.
* Follow [submission instructions](#submission-instructions) for review.

## Lesson Topic Instructions:
Verify that each item listed below has been factored into the refactor of the website to ensure high level of completion. 
### [Lesson 1: Set Up the Project](https://courses.bootcampspot.com/courses/1179/pages/1-dot-1-1-introduction?module_item_id=456037)
*Topic(s)-HMTL Page Structure, Create/Publish Git Repository
### [Lesson 2: Build the Header and Footer](https://courses.bootcampspot.com/courses/1179/pages/1-dot-2-1-introduction?module_item_id=456077)
*Topic(s)- Relative Paths, CSS Selectors, HTML Attributes
### [Lesson 3: Create the Hero](https://courses.bootcampspot.com/courses/1179/pages/1-dot-3-1-introduction?module_item_id=456116)
*Topic(s)- Form Creation, Block-level/Inline-level Elements, Relative/Absolute HTML Positioning 
### [Lesson 4: Build the Two Main Content Sections](https://courses.bootcampspot.com/courses/1179/pages/1-dot-4-1-introduction?module_item_id=456148)
*Topic(s)- img/span Elements, CSS Elements, HTML Elements for Multiple CSS Clases
### [Lesson 5: Meet the Trainers](https://courses.bootcampspot.com/courses/1179/pages/1-dot-5-1-introduction?module_item_id=456180)
*Topic(s)- CSS Float Correction, CSS Class for Multiple HTML Elements, HTML Tags over divs
### [Lesson 6: Build the Contact Section](https://courses.bootcampspot.com/courses/1179/pages/1-dot-6-1-introduction?module_item_id=456212)
*Topic(s): Reuse CSS to Avoid Duplication, CSS to Create Two Columns, Implement iframe
### [Lesson 7: Add a Privacy Policy](https://courses.bootcampspot.com/courses/1179/pages/1-dot-7-1-introduction?module_item_id=456256)
*Topic(s): Link Multiple CSS Style Sheets to Single HTML Page

# Actions Taken
## HTML Actions Taken
*Title From: `website' to `Horiseon'<br>
*Changed <`div class="header`> to <`header`><br>
*Changed <`/div`> to <`/header`><br>
*Changed <`div class="content"`> to <`section`><br>
*Changed <`/div`> to <`section`><br>
*Changed <`div class="benefits"`> to <`aside`><br>
*Changed <`/div`> to <`aside`><br>
*Changed <`div class="footer`> to <`footer`><br>
*Changed <`/div`> to <`/footer`><br>

*Changed <`div`> for class="search-engine-optimization",class="online-reputation-management", class="social-media-marketing" to <`article`><br>
*Changed <`/div`> to <`/article`><br>

*Changed <`div class="benefit-lead"`> <`div class="benefit-brand"`>  <`div class="benefit-cost"`> to <`div class="lead-brand-cost"`><br>
*Added `id="search-engine-optimization"` to the `article` tag<br>

*Changed <`img src="./assets/images/lead-generation.png" /`> to <`img src="./assets/images/lead-generation.png"`><br>
*Changed <`img src="./assets/images/brand-awareness.png" /.`> to <`img src="./assets/images/brand-awareness.png"`><br>
*Changed <`img src="./assets/images/cost-management.png"></img`> to <`img src="./assets/images/cost-management.png"`><br>


## CSS Actions Taken
*Changed `.header {}` to `header{}`<br>
*Changed `.header h1 {}` to `header h1 {}`<br>
*Changed `.header h1 .seo {}` to `header h1 .seo {}`<br>
*Changed `.header div {}` to `header div {}`<br>
*Changed `.header div ul {}` to `header div ul {}`<br>
*Changed `.header div ul li {}` to `header div ul li {}`<br>
*Changed `.content {}` to `section {}`<br>
*Changed `.benefits {}` to `aside{}`<br>
*Changed `.footer {}` to `footer {}`<br>
*Changed `.footer h2 {}` to `footer h2 {}`<br>

*Condensed `.benefit-lead {}` `".benefit-brand {}"` `.benefit-cost {}` to `.lead-brand-cost{}`<br>
*Deleted `.benefit-lead {}` `".benefit-brand {}"` `.benefit-cost {}`<br>
*Condensed `.benefit-lead h3 {}` `.benefit-brand h3 {}` `.benefit-cost h3 {}`to `lead-brand-cost h3{}`<br>
*Deleted `.benefit-lead h3 {}` `".benefit-brand h3 {}"` `.benefit-cost h3 {}`<br>
*Condensed `.benefit-lead img {}` `.benefit-brand img {}` `.benefit-cost img {}`to `lead-brand-cost img{}`<br>
*Deleted `.benefit-lead h3 {}` `".benefit-brand h3 {}"` `.benefit-cost h3 {}`<br>
*Condensed `.search-engine-optimization{}` `.online-reputation-management {}` `.social-media-marketing {}`to `article`<br>
*Deleted `.search-engine-optimization{}` `.online-reputation-management {}` `.social-media-marketing {}`<br>
*Condensed `.search-engine-optimization img {}` `.online-reputation-management img {}` `.social-media-marketing img {}`to `article img`<br>
*Deleted `.search-engine-optimization img {}` `.online-reputation-management img {}` `.social-media-marketing img {}`<br>
*Condensed `.search-engine-optimization h2 {}` `.online-reputation-management h2 {}` `.social-media-marketing h2 {}`to `article h2`<br>
*Deleted `.search-engine-optimization h2 {}` `.online-reputation-management h2 {}` `.social-media-marketing h2 {}`<br>


*Changed `Calibri` to `'Calibri'` in sections: header, aside, search-online-social<br>

# Submission Instructions
## Submission Tool 1
* The URL of the deployed application.
* Tab: `Website`
 
## Submission Tool 2
* The URL of the GitHub repository. Give the repository a unique name and include a professional README describing the project.
* Tab: `Text Entry`