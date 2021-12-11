# Horiseon-Refactor

## The Goal
Refactor code for a marketing agency so that the codebase follows accessibility standards and is optimised for search engines.

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

## The Soluion
```
HTML Semantic tags were added replacing divs using a logical structure

<header>
<nav>
<figure>
<main>
<section>
<aside>
<footer>

-----------


All images and icons have been updated to include 'alt' attributes. 


CSS file was consolidated and organised to follow semantic structure

.search-engine-optimization,
.online-reputation-management,
.social-media-marketing 
 { 
  margin-bottom: 20px;
  padding: 50px;
  height: 300px;
  font-family: "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS", sans-serif;
  background-color: #0072bb;
  color: #ffffff;
}

Alt atrributes added to images



```

## Installation
The deployed application can be opened via the link: https://bavkudhail.github.io/horiseon-refactor/
The repository application can be opened via the link: https://github.com/BavKudhail/horiseon-refactor

## Credits
Project conducted as part of The University of Birmingham Web-Development bootcamp.


