# Project: Buyers Nomorse

An app that does stuff related to price comparison.

## Erica

### NSUserDefaults

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed 
do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris 
nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in
reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
Excepteur sint occaecat cupidatat non proident, sunt in culpa
qui officia deserunt mollit anim id est laborum.

## Sabrina

### Going through eBay's API

My biggest contribution to this project was figuring our eBay’s JSON data. EBay has many different data sets, depending on which API the user calls.  We started this project with one set of JSON data that was easily found (FindPopularItems) - but it did not contain the information/parameters we needed (the ability to filter by min and max prices). I was insistent that we continue looking for the right JSON data instead of changing our project, because I knew that if the function could be performed on eBay’s website, we should be able to find data on it.

With research, we found the API call we wanted (findItemsAdvanced) - but it was difficult to find the data in JSON format. It took a whole day’s time of reading through eBay’s API Reference Guide to find the necessary data. The JSON data is hidden under URL format. In the API Reference Guide must click the link that says “See also the non-wrapped version of this URL.” Then, change the parameter RESPONSE-DATA-FORMAT to JSON instead of XML.

I found that going through eBay’ data was not straightforward. It took intuition. For example, the reference guide lists parameters for searching by min and max prices, but not on how to search for one without the other. (Hint: It’s not as simple as removing the unnecessary parameter. The parameter name has to change slightly as well.)

I learned that outside research may be just as helpful as an API guide (such as, finding out the  category ID’s of popular eBay items - for these numbers change frequently). This project also reinforced a lot of previous lessons - such as using UITextField and delegates, as well as error parsing. I practiced initializing computed class variables, as opposed to just using stored properties.

I learned to collaborate and communicate with others in using git, and in general. I learned to read through other people’s code and storyboard, and to learn from their programming and stylistic choices. I was lucky to work on this project with very talented and creative partners. 

## Shashi

### API endpoints

Sed ut perspiciatis unde omnis iste natus error sit voluptatem
accusantium doloremque laudantium, totam rem aperiam, eaque ipsa 
quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt 
explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit
aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. 
