# Code Refactor Starter Code

User Story:  
AS A marketing agency   
I WANT a codebase that follows accessibility standards  
SO THAT our own site is optimized for search engines  

Acceptance Criteria:  
GIVEN a webpage meets accessibility standards  
WHEN I view the source code   
THEN I find semantic HTML elements  
WHEN I view the structure of the HTML elements  
THEN I find that the elements follow a logical structure independent of styling and positioning  
WHEN I view the image elements  
THEN I find accessible alt attributes  
WHEN I view the heading attributes  
THEN they fall in sequential order  
WHEN I view the title element  
THEN I find a concise, descriptive title  

What I fixed:  
added website title  
switched out the div for header, nav, sections, articles and footer  
no id on the search-engine-optimization div  
changed div to img for hero and edited css  
merged css for benefit-lead, benefit-brand and benefit-costinto benefit-item  
merged css into content-item  
took out seo class for span  
added alts  
merged more css for benefit-container including h3 and img  
merged css for content div and also moved it above benefits to reflect html order  
added comments to everything  
