# UR-RICH-FSF-PT-05-2020-U-C

The purpose of this exercise was to get acquainted with some of the common tasks associated with being a junior front end developer. For our first homework assignment, we were given both an .html file and a .css file to try and do some cleaning up of the code. One of the main issues with the .html file is that in order for search engine optimization, you want to have more semantic elements than just 'div' tags. In order to achieve this I simply isolated the 'content' portion of the .html file and gave it a 'main' tag. The individual blocks within the 'main' tag were given 'section' tags. The same was done with the 'benefits' portion of the .html file except it was given an 'aside' tag with the individual blocks once again recieving 'section' tags. This helps the browser read the page easier and allows for your website to potentially be higher in the search engine list results. The .html file also had a search engine optimization link at the top of the page that wasn't working, the reason being for this is because the corresponding section closer towards the bottom of the .html file only had a 'class' attribute and not a unique 'ID' attribute that the href in the navigational portion the search engine optimization links to. The next small problem I encountered was an accidental extra '>' tag that was intended to close a tag, but it ended up being part of the text that was shown on the screen. The .css file was structured decently with however some of the selectors could be rearranged and/or grouped together. I was able to group together some, but others with the same attributes and values created major issues when I tried to group them together. This exercise has been a great example of how small errors can create larger issues on the related web page and how there is always a way to make whatever code you are working on a little bit cleaner than you found it. The activities for this section were mostly comprised of basic tasks such as linking .html and .css file paths, introducing more semantic elements, working with box sizing and screen positioning, reorganizing the .css file to be structured more similarly to the .html file, and working with the command line.
