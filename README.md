# Assignment

The assignment consists of 3 files:
1. index.html
2. main.js
3. style.css

To run the assignment, open command prompt and run- node main.js
This will create a server and run the index.html file. To view this, enter "http://localhost:8000/" in the url.

The page consists of 2 sides: one the playlist and the other the iframe to play the youtube video.
Necessary parameters are given the the Youtube API and the maxResults is set to the default value which is 5.

When the page loads, corresponsing artist videos are retrieved and on select change, the corresponsing artist videos are retrived.

Design decisions:
1. A dropdown to easily select artists from the list.
2. Results displayed below on one side and the other side shows the video. This allows user to view the search results while not navigating away from the video.
3. Each result has a thumbnail, title displaying only certain max characters. This is for good and uniform design. A playbutton is for each row to play corresponding video.

Difficulties faced:
1. I took quite sometime to find out what paraters to give to Youtube search API and the result format to be able to extract relevant details from it.
2. Displaying the video in the iframe- Initially I faced Cross Origin Request error. I was then able to resolve it by using emved function of youtube.
