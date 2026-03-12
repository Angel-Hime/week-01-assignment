# week-01-assignment

# Splash page themed on the television show 'Smiling Friends'.

Sources:
https://www.adultswim.com/videos/smiling-friends
https://www.imdb.com/title/tt12074628/episodes/?season=1&ref_=ttep
https://www.imdb.com/title/tt12074628/episodes/?season=2&ref_=ttep
https://www.imdb.com/title/tt12074628/episodes/?season=3&ref_=ttep
https://developer.mozilla.org/en-US/docs/Web/API/HTMLAudioElement/Audio
https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/min-width

__Reflection__
        
[x]    🎯 Ensure each section of the webpage is wrapped in the correct semantic tags, ensuring that includes a <header>, <nav>, and <footer>.

[x]    🎯 Implement CSS absolute positioning to overlay text on an image or another element.

[x]    🎯 Utilise CSS Flexbox to create a flexible and responsive layout, particularly in the <nav> element.

[x]    🎯 Ensure all image elements (<img>) and background images are correctly implemented with accurate file paths.

[x]    🏹 Create a “back to top” button.

[x]    🏹 Implement smooth scrolling for internal links to improve user experience.

[x]    🏹 Implement a hover effect on buttons to make them more interactive.

[x]    🏹 Create a basic footer with social media icons that link to social media pages.

[x]    🏹 Add a background music track that plays automatically when the website loads.

Making sure everything would fit the page design that I wanted to follow through with was a little bit difficult; I didn't know how to shrink images to allow for divs or nav sections to be smaller if the user shrunk their browser window; I struggled making sure that the links would wrap and fit nicely into the window if the window was smaller.

I believe that the images I used allowed for the UX to be a little better than when I was struggling with sizing the images manually. The solution here was to use a fixed minimum pixel count and a fixed header and footer to enforce a UI scroll; purposefully avoiding a wrap on the 'episodes section' that destroyed the UI. This did preclude me from having an static footer akin to the example given but at the time I wasn't sure how I could keep the full footer length with the window being resized, it would only be the length of the window due to having width set to 100% but I found that I could simply retain the length my using min-width at 100% and the max-width at 100%. I chose to keep the fixed footer as this was more aesthetically pleasing.

# As this was at the beginning of the bootcamp, I wrote the following reflections for this project:

A big struggle of mine is that I over complicate things; I find it difficult to come up with a structured plan to follow. I think I would appreciate some help with approaching projects; how best to do a wireframe; and, how best to plan out the actual pseudocode.

Even considering a design is difficult as I don't have that kind of creative brain, so this sort of project will continue to be difficult for that purpose. I have no real grasp on the 'design' aspect of development, so even thinking of something took me a couple hours.
