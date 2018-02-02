# UnifyID_RGB_Bitmap_Generation

# Problem Statement

This challenge is programming language agnostic! Pick whichever language you're most comfortable with. Random.org is a web front-end to an atmospheric noise sensor, which can give us pretty good random numbers. It's the reverse from a noise cancelling filter, since it cancels everything BUT the noise. Weather conditions, solar flares, a full-moon can have little impact on this, since it focuses on getting the purest white noise possible from their hardware sensors. If you too think this is cool, you'd be thrilled to try our challenge:

1. Using the HTTP API for random.org (https://www.random.org/clients/http/) we will ask you to get truly random numbers. Look out for the guidelines, or you may get banned!

2. Using these random numbers create one of the following, to get bonus points:

- An RGB bitmap picture of 128x128 pixels. (70 points)

- A white noise WAV sound sample of 3 seconds (70 points)

- An RSA key pair (We would discourage you from implementing your own textbook keypair implementation based on exponents and GCD, 100 points)

# Problem faced

One major problem faced was the limit of 10K maximum random numbers that can be requested at a time in 1 API request while 128 * 128 bitmap requires 16384 numbers. Also, after testing for several times, I got blocked and could not further test the code!

# Solution

I started with understanding the API format and requirements on the random.org's API description page. I have tried solving the RGB image generation problem using Javascript. 
