# Horiseon-Refactor

## The Goal
Refactor code for a marketing agency so that the codebase follows accessibility standards and is optimised for search engines.

### User Story
As a marketing agency I want a codebase that follows accessibility standards so that our own site is optimized for search engines

![home-page screen-shot](https://raw.githubusercontent.com/BavKudhail/horiseon-refactor/main/assets/images/homepage-snippet.JPG)

### Acceptance Criteria in order to meet goal
* Ensure accessibility standards are met
* Ensure semantic HTML elements are used
* Ensure elements follow a logical structure independent of styling and positioning
* Ensure image elements contain accessible alt attributes
* Ensure heading attributes fall in sequential order
* Ensure 'title' element contains a concise, and descriptive title

### Additional Criteria
* Ensure all links are functioning correctly
* Ensure CSS selectors and properties are consolidated and organized to follow semantic structure
* Ensue application's CSS file is properly commented

## The Learning Loop
### Research
In order to refactor the site to meet accessibility standards I began to research the following topics. 
* HTML Semantic Elements
* HTML Accessibility 
* CSS Consolidation
* Using Markup language

### Identifying problems in code 
```
Div used to structure entire HTML

<div class="header">
  <div class="content">
  <div class="benefits">
<div class="footer">
 
 
No title defined leading to poor SEO

  <title>website</title>
  
  
Heading elements not in sequential order. H2 element in footer, whilst h3 is in site content

  <div class="footer">
        <h2>Made with ❤️️ by Horiseon</h2>
   </div>
 
 
 No alt attributes
 <img src="./assets/images/social-media-marketing.jpg" class="float-left" />
 ```
 
 ### Implementing solutions
 
 ```
 Added semantic tags to replace div tag
 
 <header>
 <nav>
 <main>
 <figure>
 <section>
 <aside>
 <footer>
 
 
 Added Title

 <title>Horiseon Social Solution Services</title>


 Added missing ID to nav link

 <section id="search-engine-optimization" class="search-engine-optimization">
 
 
 Added alt attributes to image files
 
 <img src="./assets/images/search-engine-optimization.jpg" class="float-left" alt="seo notebook on desk" />
 
 
 Adjusted headings to sequential order and adjusted CSS appropriately**
 
 <footer class="footer">
        <h4>Made with ❤️️ by Horiseon</h4>
 
 
 
  Consolidated CSS
 
 .search-engine-optimization img,
.online-reputation-management img,
.social-media-marketing img {
  max-height: 200px;
}

.search-engine-optimization h2,
.online-reputation-management h2,
.social-media-marketing h2 {
  margin-bottom: 20px;
  font-size: 36px;
}
  ```
 
 
## Installation
The deployed application can be opened via the link: https://bavkudhail.github.io/horiseon-refactor/

## Credits
Project conducted as part of The University of Birmingham Web-Development bootcamp.


