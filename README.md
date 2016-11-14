# Project: Buyers Nomorse

A shopping app called “!impulse” that gives you alternative buying choices for the price of the item you have searched for.

## Erica

### Facebook Integration

Goal: Allow users to sign-in and share interesting findings with friends.

#### Part 1: Configuring the Facebook SDK for iOS 

* SDK == Software Developer Kit
* A set of frameworks that allow us to _“easily”_ integrate our apps with Facebook
  * "A framework is a hierarchial directory that encapsulates shared resources in a single package" 
  * Examples of shared resources include: shared library, nib files, image files, localized strings, header files, and reference documentation 
  * [More on Frameworks](https://developer.apple.com/library/content/documentation/MacOSX/Conceptual/BPFrameworks/Concepts/WhatAreFrameworks.html)
* [Link to Getting Started with the Facebook SDK for iOS](https://developers.facebook.com/docs/ios/getting-started/)

#### Part 2: Implementing Capabilites and/or Other App Events

#### Other Resources




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
