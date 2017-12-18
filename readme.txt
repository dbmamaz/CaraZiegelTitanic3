Summary:
I am looking at the Titanic dataset.  I chose an easy set because I have never worked with javascript at all, and wanted to start slowly.  The story I want to share is that, when the Titanic crashed, the more expensive your ticket was, the better your chance of survival.  In other words, a larger portion of 3rd class ticket-holders died than did 2nd class, and the 1st class ticket holders had the highest survival rate.

Design:
 * My first run of survival by class was the default bar chart, but I was happy to have anything showing up!
 * A single bar for each class, representing survivors, did not give enough information to really understand the likelihood of survival for each class, but the side-by-side bar was much clearer.
 * I added a legend and custom axis labels to help communicate the information
 * I changed what field was used to summarize the passengers in order to get an accurate count.  I later realized I could have changed the way Dimple was aggregating the data, but since it was already correct, I left it that way.
 * I changed field names in the data to make the hover text make more sense


Feedback:
 1. I showed my adult son (Son #1, Orion) my first version, with a single bar per class.  He said it was surprising that more 3rd class passengers survived than 2nd class.  But thats because this is raw numbers, not percent.  Clearly I need to do more work to show the story I'm trying to tell, that the higher class passengers survived at a higher rate.  

 2. I showed my second version, with side-by-side bars to my younger son (Son #2, Raven).  He was mostly confused by the lack of good labels, as the default data labels were hard to understand, but once I explained that, he could easily see the information.  His summary of the story was that in first class, more people survived than died, in 2nd class, it was about even, and in third class, more people died than survived. He also found it interesting that a similar raw number of ppl survived in each class.

 3. After adding labels, I showed my chart to my husband. He noticed that the data was flat-out wrong!  The chart was showing over 200,000 passengers on the boat!  Oops!  He also suggested changing the bottom labels.  

After I fixed those, we discussed doing a stacked bar instead of a side-by-side bar, but agreed it would actually be harder to visualize the numbers that way, especially because the large number of 3rd class passengers would throw the scale off even more.  However, he suggested I change the lables from Survivors and Non-survivors to Survivers and Deaths.


Resources:
	* I used the example code provided by the course as starter code
	* I used javascript code from the forums to alter the data
	* I used W3schools to figure out how to alter the javascript code
	* I also used stack overflow and a few other code samples I found on the web
	* I used Dimple's documentation, tho I found it not particularly helpful





