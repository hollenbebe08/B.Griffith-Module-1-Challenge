# Project Title: Refractor of Horiseon Website

⚙️ Main goals of the project: </br>
    1. Update codebase to follow accessibility standards and optimize the site for search engines </br>
    2. Ensure that the code follows semantic HTML </br>
    3. Ensure that the CSS code is cascading correctly and is free of repeating code</br>


✅ Main goals will be achieved when the webpage meets accessibility standards. The criteria for having an accessible website are: </br>
* When I view the source code - then I find semantic HTML elements </br>
* When I view the structure of the HTML elements - then I find that the elements follow a logical structure independent of styling and positioning </br>
* When I view the image elements - then I find accessible alt attributes </br>
* When I view the heading attributes - then they fall in sequential order </br>
* When I view the title element - then I find concise, descriptive title </br>

## 🗒️HTML File Updates:

**Changes made to fulfill criterias: When I veiw the source code - then I find semantic elements; </br> When I view the structure of the HTML elements - then I find that the elements follow a logical structure independent of styling and positioning** </br>

* Adjusted the head and body to be tabbed in from HTML and removed unnecessary line spaces.
* Changed the div tag for the header to be a header tag as well as its respective closing tag.
* Changed the div encompassing the Ul to be a nav tag.
* Changed the div tag for the hero to be a section tag and moved the closing tag for the section to it's appropriate spot at the bottom of the code block. Split the hero section from the SEO, Reputation, and Social Media Section.
* Changed the tags for the "search engine optimization", "online reputation management", and "social media marketing" content blocks to article tags and added respective closing tags. Also enclosed the article tags within open and ending section tags.
![alt text](./screenshots/screenshot-two.png)
* assigned the class "content" to the section encompassing the SEO, rep, and Social media articles.
* Changed the div tag for the benefit to be a section tag as well as its respective closing tag. I left the tags inside of the benefit section as divs since their content isn't independent content.
* Changed the div tag for the footer to be a footer tag as well as its respective closing tag.

</br>
</br>

**Changes made to fulfill criteria: When I view the image elements - then I find accessible alt attributes** </br>
* Added alt attributes to the "search engine optimization", "online reputation management", and "social media marketing" images.
* Added open alt attributes to the benefit section images. I did not give them any sort of description since the images are icons and not vital to understanding the page.
![alt text](./screenshots/screenshot-three.png)

</br>
</br>

**Changes made to fulfill criteria: When I view the heading attributes - then they fall in sequential order** </br>

</br>
</br>

**Changes made to fulfill criteria: When I view the title element - then I find concise, descriptive title** </br>
* Changed the title in the head to be Horiseon Homepage following semantic html to indicate where the user is located on the website.

</br>

## 🗒️CSS File Updates to ensure that the CSS code is cascading correctly and is free of repeating code:

**Changes made to Header Section:**

**Changes made to Hero Section:**
* Created its own section in the HTML file and made the hero class in the CSS file its own.

**Changes made to SEO, Rep, Social Media section**
* All of the styling for the search engine optimization, online reputation management, and social media marketing articles was moved up in the CSS file to be under its own section.

**Changes made to Benefits Section:**

**Changes made to the Footer Section:**
* Moved the footers css styling to be under the header styling


