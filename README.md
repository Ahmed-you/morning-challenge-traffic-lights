**Author**: [@finnhodgkin](https://github.com/finnhodgkin)



## Your task

Your task is to replicate the traffic lights shown above. The only file you'll
need to edit is `script.js`. Hopefully the instructional comments will speak for
themselves.

### Part 1:

Light up the first traffic light in the following order:

+ :green_apple: green
+ :sun_with_face: yellow
+ :red_circle: red
+ :red_circle::sun_with_face: red & yellow
+ :green_apple: green

### Part 2:

Display the red light for longer:

+ :green_apple: green
+ :sun_with_face: yellow
+ :red_circle: red (3 seconds)
+ :red_circle::sun_with_face: red & yellow
+ :green_apple: green

### Part 3:

Loop the light so it plays forever.

> Hint: recursion worked for me...

### Part 4:

Loop the second light with the following rules:

+ Green should show only when the other light is red.
+ When transitioning from green to red, show yellow.
+ If the other light is green or yellow, show red.
+ When transitioning from red to green show yellow and red simultaneously.

:vertical_traffic_light: If successful you should see something like the
gif above. :tada:
