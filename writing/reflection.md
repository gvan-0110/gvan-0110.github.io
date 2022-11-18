# CMPSC 480: Portfolio project reflection

To begin with working on my website, I first used fernfolio's code as a template.  This is because I wanted to use the code it already had to learn how to work with 11ty, css, and njk files.

One of the challenges I faced when building my site was modifying the main page.  The issue with the main page was that I needed the header to be different than all the other pages on the site.  To fix this issue, I create a seperate njk file for both the main page's header and page base code.  This allowed me to have two seperate formats to split between the two parts of my site, rather than one global format.

One other issue I faced was understanding how and where the different files in the website's template connected together.  For example, it wasn't until I studied the code for a while that I realized njk files, md files, and scss files need to have the same file names to detect eachother.  

One other thing that stumped me for a bit was the `Collections` call in the code that happened in the njk files.  I wasn't sure at first where it was being referenced from since I didn't see an area where it was created.  Then I found out that collections get's its info from the tags you set in the markdown files for each page.

The main goal for my website was to be catered for academic audiences.  While I do have my resume on the website, I make a main focus in what I am currently learning, and the projects I have done in the past from previous research.  I also make it a point to discuss my main interest in computer science within my about me page.

Due to the previous work we have completed, I was able to narrow down a field of research I am most interested in to discuss on the site.  I also included my newest resume that we worked on in a previous assignment.  Finally, I submitted the cleaned up versions of my projects on my project's page for others to view.  Although, my AutoMusicSort project is still private since it is currently my senior project and being worked on.  For now, the project has a description and will be published publically when it is finished.
