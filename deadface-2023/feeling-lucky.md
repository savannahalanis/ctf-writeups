# Deadface 2023 Writeup
Name - Feeling Lucky
Author - Shamel
Category - OSINT
Points - 250

## Challenge Description

It seems DEADFACE was able to track Alejandro's movements again. They shared this photo they took from Alejandro. Knowing this location might help us intercept the DEADFACE member who's looking for Alejandro.

Submit flag as flag{City, state code, zip code}
Example: flag{Allison Park, PA, 15101}

![Wide shot of a Lucky's supermarket parking lot, with mountains in the background]()

## My Process

The two things I noticed about the image was the store Lucky and the mountains in the background.

I first tried reverse image searching, but after a bit of scrolling, I found no images that matched. It was the same thing with Google Maps.

I then just searched up Lucky on regular Google and found [the brand's website](https://luckysupermarkets.com/). On the top of the page, the logo matched with the logo in the picture, so I knew this was the correct brand. I looked at the locations listed on the website, but there was a long list of them, without pictures of the exterior.

Next, I searched up "Lucky Grocery Store" on Google Images. One search result popped up and it contained the same looking exterior as the image! I visited [the website associated with the image](https://www.luckylowprices.com/lucky-low-prices.html) and scrolling down I saw four different places listed on the website, all locations in Utah. I visited the the first sight on Google Maps and saw mountains!! But the exterior was different one than was shown in the image on the site. So I searched the next locations and saw that there were both mountains and the correct exterior. 1585 W 3500 S, West Valley City, UT was the correct location. Google Maps provided me with the zip code of 84119.

So, the flag was
flag{West Valley City, UT, 84119}
