### Lab #6: Red Line

#### By Ben Tanen

This lab involves using the Google Maps API to create a map of pins showing the current location of the MBTA's Red Line trains.

In an ideal sense, this lab would work by using both the Google Maps API and the XMLHttpRequest class to obtain train information from the MBTA's provided JSON file. Once the file is obtained, the information could be parsed using `JSON.parse()` and could then be used to drop pins at the individual train locations.

However, a major limitation of this lab was Javascript's Same-origin policy. Since the lab was run locally on a computer, JS only had the capability to load data from the same origin (the local computer) in order to run the page. Even though the MBTA openly provides the JSON information about the trains, JS cannot access it so our train mapping site will not work. In order to get the page to full work, we must implement some solution to work around Javscript's same-origin policy, which would be quite simple (if it were allowed within the lab).

Because of the problem discussed above, the page does not work as planned. Instead, at the moment, the page only displays one pin at the Davis Square T-stop. As stated above, there is the possibility to improve on this with a work-around for Javscript's same-origin policy.

All of the code was written by Ben Tanen (help provided from Google Maps API and Mozilla documentation). Overall, the lab took approximately 60-min.