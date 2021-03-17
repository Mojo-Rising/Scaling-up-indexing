# Assignment: Scaling up - Indexing

*PLEASE READ THIS **ENTIRE** DOCUMENT FIRST*

* [the assignment](#the-assignment)
* [submitting-your-work](#submitting-your-work)


## The assignment

Download this repo and edit the index, use the video for guidance.

* Determine the start and end date of your data. Use d3.sort(d3.ascending) to make sure the first datapoint is the earliest and that the last datapoint is the latest.
* Use d3.timeMinute to create a timerange containing every minute between the start and end date
* Create an indexedData object with an empty object for every minute in the timerange. Use formatTime to format the key you use.
* Loop over btcData and using the formatted time attribute, place the whole object into the indexedData object at the correct minute position.
* Adapt the tooltip so that it retrieves the price data using the minute key. You can create the key using the inverted x coordinate of the mouse.

* Optionally, filter the data going into the line generator so that it only uses 1 datapoint out of every `btcData.length / width`


## Submitting your work
Create a new branch called **gh-pages** and upload your local work into this branch. Submit a new **pull request** and make sure to put the (working) **GitHub Pages URL** in the comment section. 
