# Code Refraction 
In this challenge, I had to go over the starter code and make changes to the code in order to optimize the lines of code.

Firstly, i had removed the <div> tags on lines 13 and 25 to <nav> tags in order to set the links to work, however in doing so put them in an unordered list using bullet points. list made them a literal list and i could not find a way to make them appear side my side again.

EDIT: In the CSS i fixed the <div> on lines 35 and 39 and changed it to nav in order to give the links in the list the correct style and not the defoult. I also attempted to float it to the right in order to have it positioned right, however this did not work as it would over-ride the inline block property.

In addition, the hyperlink "Search-engine-Optimization" was not working, so on line 29 I added the id= to make sure thet the link would work.

Next i noticed in the CSS that the font style was repeated a lot, which i think is not necesarry and therefore applied it to the <body> and removed all the redundant instances of it.

