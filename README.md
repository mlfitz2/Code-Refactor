# Code-Refactor

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



