# Horiseon-Code-Refactor

Updated the site Title from "website" to "Horiseon."

In Navbar, "Search Engine Optimization" button not working because element ID was missing from the section being linked to. Added this, restored functionality. 

Gave the header a semantic <header> tag instead of <div>, then in CSS changed the style rules of the .header class to be just the <header> element. 
Gave the navigation bar a <nav> tag to replace div, then updated CSS so the applicable rules would still apply.
Changed the <div> tag of the main photo to <figure>. In this case I kept the .hero class so that the rules would apply to this photo only, as before. 
Replaced the <div class="content"> with the semantic element <main>. Updated .content to main in CSS as well.
Gave <section> semantic title to the three sections: Search Engine Optimization, Online Reputation Management, and Social Media Marketing. 
Gave the sidebar an <aside> element, and the three points within it with <section>.
Replaced <div class="footer"> with <footer>, and updated the corresponding CSS tags.

Added alt descriptors to the images and icons. 

Slightly changed the color of "seo" in Horiseon to emphasize the SEO pun that they intended. The other color was too similar to the rest of the letters and it wasn't clear if that was on purpose or if I was just seeing things. 

In CSS:
Removed "header" from the "header h1" and "header nav" rules. It was redundant since the only h1 and navbar were in the header. 
The main section had separate classes for each of the three items, even though the CSS rules were identical. I replaced these classes with one .services-provided class, and cut down the three CSS rules to one that was applicable to all three. I did the same for the corresponding images and headers. I consolidated the sidebar in the same way, and moved the sidebar's rules down to below the Main one to match the order in which they appear in CSS.





Code Refactor of Horiseon Website

In this project, I improved upon the existing site by:
    - Fixing errors related to functionality
    - Improved accessibility and Search Engine Optimization of the site by replacing the <div> elements with semantic elements, and adding features for accessibility
    - Cleaned up redundant aspects of the CSS stylesheet to improve readability of the code. 

Errors fixed: I updated the site title from "Website" to "Horiseon," the name of the company. Then fixed the non-functional navbar button by assigning an ID to the element it was linking to, since that was missing. 

Accessibility and SEO: I replaced the <div> tags with semantic elements, and updated their corresponding CSS rules to maintain the original style. <header>, <nav>, <figure>, <main>, <section>, <aside>, and <footer> tags were incorporated into the revised version. Alt descriptors were added to all images and icons to optimize accessibility. 

Clean up the code: There were several instances where rules were applied to more elements than was necessary, for example "header h1." Since there is only one h1 I removed "header" from the rule since it is unncessary and impedes the ease of reading the CSS stylesheet. Likewise, the main section and sidebar had the same rules listed three times, once for each box they were being applied to. I cleaned this up by applying one class to the text in question and having one CSS ruleset to apply to them all. 

In the header, the "seo" in "Horiseo" was a slightly different shade of white, as a pun on the SEO services they provide. This shade was very similar to the rest of the word, resulting in it being unclear if they were a different shade or if there was just a shadow on the screen. I changed the shade to a slightly more noticeable one to provide clarity while maintaining the aesthetic appeal. 

