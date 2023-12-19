# Horiseon Refactor Challenge

## Description 

This project is the first challenge of many in the 2023 edX Front-End Development Bootcamp.
It is a refactor project, where the main goal is rework the source code (HTML/CSS) in a one page website of a fictional Marketing Agency called Horiseon.

**A snippet from the challenge description:**
"Web accessibility is an increasingly important consideration for businesses. It ensures that people with disabilities can access a website using assistive technologies such as video captions, screen readers, and braille keyboards. Making a website accessible is also good for business for many reasons, one of them being that accessible sites are better positioned in search engines like Google. It also helps companies avoid litigation that can occur when people with disabilities cannot access their website.
Even though accessibility is a broad topic that can include complex requirements, your tech lead has given you a small list of specific criteria to satisfy the project. These criteria are documented below in the Acceptance Criteria. 
To impress clients, you should always go the extra mile and improve the codebase for long-term sustainability. For example, make sure that all links are functioning correctly. Also, rework the CSS to make it more efficient by consolidating CSS selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page.

An **important** rule was to follow when working with someone else's code is the **Scout Rule**, which recommends that you always leave the code a little cleaner than when you found it".

---

## Installation


The work environment has been Visual Studio Code for this project, with the help of Firefox Developer Edition's built-in faetures for examining the live page.


## Original state and findings

**HTML**

The original source code was very loosely written, such as the webpage had no proper title, meta tags had been missing,
and the sections in different elements of the page has been stated as 'div's. Here is below some examples:


![Head](assets/screenshots/head.png "Head") 

The head is missing a proper website title, meta tag such as title, keywords, description, canonical and so on.


![Nav](assets/screenshots/nav.png "Nav")

Navigation 


![Content](assets/screenshots/main_content.png "Content")

The main content seem overcomplicated, and has a lot of white space.


![Right](assets/screenshots/right_section.png "Right")

Right section suffers from the same issue as the main


**CSS**


![Main](assets/screenshots/social_css.png "Main")

These elements has the same values, therefore unnecesary to duplicate


![Right](assets/screenshots/benefit_css.png "Right")

The right section seems to have the same issue


## Solved Issues

**HTML**


![Head](assets/screenshots/meta_after.png "Head") 

The head section had been updated with title and neccesary meta tags for both accessibility and seo purposes.


![Nav](assets/screenshots/nav_aft.png "Nav") 

Navigation


![Main](assets/screenshots/main_aft.png "Main") 

Main content section rework, elements now fall under the same class and attributes had been changed for accessiability.


![Aside](assets/screenshots/right_aft.png "Aside") 

The same with 'aside' section


![Aside](assets/screenshots/footer_aft.png "Aside") 

Morevover, 
For a more professional look, 'Made with love' part had been erased from footer.



**CSS**

![Head](assets/screenshots/header_aft.png "Head")

Header and navigation prooperly named.


![css](assets/screenshots/css_rework.png "css")

As elements had been polished and became part of the same classes, a more streamlined css file was the result.


![seo](assets/screenshots/add_logo_aft.png "seo")

The "logo" had a part which emphasizes the main mission of the company. There is no control in the original css file.
It is worth to emphasize it, as it helps with UX.





**Site shot**

![Site](assets/screenshots/site_new.png "Site")




## License

The project served under the MIT License.
The MIT License is a permissive free software license originating at the Massachusetts Institute of Technology (MIT) in the late 1980s. As a permissive license, it puts only very limited restriction on reuse and has, therefore, high license compatibility.



---

## Badges

Built with:

![Static Badge](https://img.shields.io/badge/63%25-63%25?label=html)
![Static Badge](https://img.shields.io/badge/37%25-37%25?label=css)



## Features

The actual version (1.0) released as an MVP product, which hence covers challenges requirements, the code will go through extensive rework from time to time, to add out-of-scope features, such as responsivity.


---
(c) 2023 oIdiOn. All rights thrown out of the window.