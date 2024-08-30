## What are these files?

Nearly everything in this repository utilizes the API that NOAA offers as a part of their Weather Service. Inherently each will give the weather in the Utah Valley in a format that utilizes a Graphic User Interface (GUI) through different Python libraries and APIs.

## drawingAPIs.py

This is a program which, among other packages, utilizes TKinter to display a sleek and efficient representation of what the weather will look like on the next hour. Please see the top of the file for other dependencies.

## weatherPage

This program is a little more complicated in that it utilizes, among others, Django. There is a bit of a "gotcha" in that, while the project itself is called weatherPage, the only page that actually shows the weather is greet.html under hello. In fact, everything of note was built in the hello app as a means of maintaining better organization.
Another point of note is that, in addition to the dependencies referenced in each file, hello/index.html utilizes Bootstrap and, in this case, is aided by django-bootstrap-v5. 
