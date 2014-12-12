### Marauder's Map

This project uses a combination of Google Maps API and XMLHttpRequest to obtain geo-location information about an array of characters and students. These characters and students are plotting on the map, as well as the user's current location (displayed as an image of TimmyBurch from South Park). The polylines are drawn between the user (Timmy) and all of the characters that are plotted (including Carmen San Diego, Batman, Prof. Hescott, etc) and the distances between the characters are shown in an overlay box.

See the assignment [here](http://ben-tanen.github.io/comp20/mmap/).

As of writting this, all of the assigned aspects of this assignment were implemented correctly.

All of the code was written/edited by Ben Tanen. However, some functions/algorithms were provided with some help. 

1. The code to implement multiple infowindows on the map markers was originally found [here](http://stackoverflow.com/questions/11106671/google-maps-api-multiple-markers-with-infowindows)
2. The algorithm/function to calculate distance between two google map coordinates can be found [here](http://stackoverflow.com/questions/1502590/calculate-distance-between-two-points-in-google-maps-v3) (used to calculate distances, index.html:160/164)
3. The function to sort an array of objects by a single key can be found [here](http://stackoverflow.com/questions/8837454/sort-array-of-objects-by-single-key-with-date-value) (used to print out the character distances in order, index.html:92)

The assignment took approximately 2-3hours, written over the course of a few days.
