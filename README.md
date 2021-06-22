# Improve Influencer Marketing for Luxuary brands
Datathon of [Launchmetrics](https://www.launchmetrics.com/) and ESCP in 2020. The goal was to increase the revenue from Instagram posts.

<p align="center">
<img src="./images/Launchmetcis.png" alt="" width="600">
</p>

## Business context
<p align="center">
<img src="./images/Challenge.png" alt="" width="700">
</p>
<br><br>

## My solution

- First download around 20K instagram images of company's influencers
- Vectorized the color properties, 1. Colourfulness 2. Saturation 3. Brightness and 4. Color ratio
- For 1, calculated the differences between RGB colors, and took variance as the vector
- For 2 & 3, used took the values that are calculated with OpenCV package
- For 4, used HSV color-space, classified each pixel into 8 colors and divided by total number of pixels in the image

<p align="center">
<img src="./images/Color property.png" alt="" width="600">
</p>
<br><br>
<p align="center">
<img src="./images/Result.png" alt="" width="600">
</p>
<br><br>
<p align="center">
<img src="./images/Suggestion.png" alt="" width="600">
</p>
