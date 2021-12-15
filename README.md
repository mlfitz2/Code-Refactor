Code Refactor of Horiseon Website

Site URL: https://mlfitz2.github.io/Horiseon-Code-Refactor/
GitHub Repository URL: https://github.com/mlfitz2/Horiseon-Code-Refactor

In this project, I improved upon the existing site by:
    - Fixing errors related to functionality
    - Improved accessibility and Search Engine Optimization of the site by replacing the <div> elements with semantic elements, and adding features for accessibility
    - Cleaned up redundant aspects of the CSS stylesheet to improve readability of the code. 

Errors fixed: I updated the site title from "Website" to "Horiseon," the name of the company. Then fixed the non-functional navbar button by assigning an ID to the element it was linking to, since that was missing. 

Accessibility and SEO: I replaced the <div> tags with semantic elements, and updated their corresponding CSS rules to maintain the original style. <header>, <nav>, <figure>, <main>, <section>, <aside>, and <footer> tags were incorporated into the revised version. Alt descriptors were added to all images and icons to optimize accessibility. 

Clean up the code: There were several instances where rules were applied to more elements than was necessary, for example "header h1." Since there is only one h1 I removed "header" from the rule since it is unncessary and impedes the ease of reading the CSS stylesheet. Likewise, the main section and sidebar had the same rules listed three times, once for each box they were being applied to. I cleaned this up by applying one class to the text in question and having one CSS ruleset to apply to them all. 

In the header, the "seo" in "Horiseo" was a slightly different shade of white, as a pun on the SEO services they provide. This shade was very similar to the rest of the word, resulting in it being unclear if they were a different shade or if there was just a shadow on the screen. I changed the shade to a slightly more noticeable one to provide clarity while maintaining the aesthetic appeal. 


TEST TEST TEST


