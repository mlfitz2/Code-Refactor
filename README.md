# Code-Refactor

Updated the site Title from "website" to "Horiseon."
In Navbar, "Search Engine Optimization" button not working because element ID was missing from the section being linked to. Added this, restored functionality. 
Gave the header a semantic <header> tag instead of <div>, then in CSS changed the style rules of the .header class to be just the <header> element. 
Gave the navigation bar a <nav> tag to replace div, then updated CSS so the applicable rules would still apply.
Changed the <div> tag of the main photo to <figure>. In this case I kept the .hero class so that the rules would apply to this photo only, as before. 
Replaced the <div class="content"> with the semantic element <main>. Updated .content to main in CSS as well.
