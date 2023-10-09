![Screenshot 2023-10-08 224310](https://github.com/dogtherobot/WA/assets/123636233/0ea6f708-7551-4db4-81f9-60c5d548aa45)

# Methodology:
I used the RGB color codes for the cones to get the points of the cones, which I then used to get best fit lines using the statistics slope and minimum and maximum points of x and y.

# What I tried:
I tried to get the RGB codes for the cones; however I believe in a more complex environment this method wouldn't be as successful. This is because in more complex environments like traffic there will be closer colors and a secure AutoDrive should be able to understand its surroundings very accurately.

# Modules used:
OpenCV for image analysis and line drawing.
Stats from SciPY for getting the mean and intercept to make a function for the paths.
Numpy to get RGB color codes.
