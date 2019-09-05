
# MilestoneProjectOne

 GitHub pages link:https://davewalsh3.github.io/MSPone/.
Band Website - The Monkees
<h3>Brief</h3>
For my first milestone project I chose to create a website for the band The Monkees.
The band were quite big in the 60's era so I have chosen that theme for aspects of my page including images and colors used.
Using supplied images, video and audio I compliled a comprehensive website that users can use to interact with the band in the method they choose, whether it be viewing slideshows of previous album art via automatic transition carousel, viewing a music video or listening to the bands backcatalogue of select songs.


As the band has been around quite a while , I feel the audience would be an older demographic and it is for this reason I used muted 60s primary colours, a 60's swirl background imageand a simple interface so that the website is easily accesible for all users.
I have a variety of links throughout the website to enable users to quickly access points of interest as they come accross them.



<h3>UX</h3>
As a user of this site, I want to find all the information, or have the ability to locate it, quickly and easily on one website.
As a fan my main wants from a website like this are - information on the band, any relevant news and future live shows.
As a 'potential' fan, I would like some insights into the history of the band, pictures of the members, samples of audio and video and the ability to purchase material from the band website.
I used the the Balsamiq app for creating my mockup initially. Although the final design changed slightly as I progressed in its creation.
Link : https://github.com/Davewalsh3/MSPone/tree/master/assets/wireframes 
(Requires Balsamiq Application & Zip Software to extract and run)

<h3>Features</h3>
This website comprises of a main navbar, fixed to the top on all screen sizes which allows users to easily navigate the page to different sections. I decided to create the page as one long continous page with links in order to allow a one-directional scroll action to be the only movement required in order to access further sections and content. The navbar is collapsable when minimized to smaller screen sizes for ease of use on mobile devices.
Bootstrap4 was used in order to utulize a simple grid layout for the website and for the creation of album cover carousel as the main landing feature. 
After the features there is a Biographics section, where photo's of Band members appear alongisde a piece of descriptive text pertaining to the member pictured. At the end of each Band member feature, ther is a 'Read more..'' button which redirects the user to further information that can be found on Wikipedia.
The next feature is a list-group container highlighting future shows the Band will be performing. It details the location , date and ticket status is an easy to read table.
The contact section follows this and informs the user on how to get in touch with the band directly through the online form presented. There is also an informatial header box above which informs potential clients that the band is available for bookings.
Social Channels are the only feature of the footer element. There are familiar small scale icons used here to redirect the user to Band-related social media website, either Official or Fan made.

<h3>Features Left to Implement</h3>
For the future of the project I would like to implement a subtle animated background feature where the background-swirls image I have used currently, would slowly reveolve on its center point. This would really exaggerate the 60's theme I was going for with this design.
I would also like to further develop the store section of the website and enhance the audio player with JQuery.

<h3> Problems Encountered </h3>
I was unable to load video to html code, so instead I embedded a youtube video in its place.
I was unable to test in safari as I could not access github through that Browser, from thorough testing using devtools on Google Chrome I reached a funtional level of expected responsiveness from iOS phone screen types.
I had to spend quite alot of time to understand and make the picture carousel work accross most screen types, though I chose to remove it from appearing on extra small screens as it would take too much time for little actual benefit to the user.
<h3>Testing</h3>

I utilized w3 html & css validator online in order to test my code. I found various discrepencies in my work such as incorrent syntax and formatting . My links to fontawesome were flagging also as as vertical sign (|) was stated as 'not being allowed'. I did not find however that the code was affected by this rule, and further attempts to address it by converting the code using url-escape-text did not seem to alleviate the highlighted error. 
I also used css autoprefixer which is a PostCSS plugin, that parses your CSS and adds vendor prefixes to your CSS Code. Though after further research into this programme, I decided to role back to the style.css version I had before I applied the prefixer, as I discovered that it is becoming an less used application for Developers today.

My footer links all redirect to Monkees' related social media channels where available, and generic social media channel homepages when unavailable on all screen sizes..

All links will redirect to the specified content section of the page, or free-to-browse Wikipedia pages associated with the content.

By clicking on the links in the navbar you will be redirected to content of the page titled in the nav. this makes aceess to desired content instant and intuitive.
A smooth scroll CSS function was applied to generate a more pleasent user experience.

This site was tested for responsiveness on all the most popular browsers (Chrome, Internet Explorer, FireFox, though I was unable to load on Safari due to "not being able to establish secure connection" on my PC , Unsolved network issues that remain) and on mobile devices such as samsung s5, iphone 6/7/8/x ipad pro and onto larger screens. During the testing phase, I had my features change position depending on screen size, I added some media queries to counter this. I also at this time fixed my background image in a static positon.

<h3>Deployment</h3>
This project was created in an AWS CLoud 9 environment following its transition from original Cloud 9 .
This site has been deployed using GitHub pages. The deployed site will update automatically upon new commits to the master branch.
In order to run this code please paste the index.html style.css and assets/ folder to your IDE.
To run this file locally, you can clone this repository directly into the editor of your choice by pasting git clone https://davewalsh3.github.io/MSPone/ into your terminal.


<h3>Credits</h3>
Content
Open source content provider Wikipedia is where I sourced some of my block text information relating to the monkees.
Last Rose Studios for the audio player and playlist code.
w3 online code validator.


<h3>Media</h3>
Images were obtained from Code Institute github repository made available for this project type.
Additional images were sourced from free image site http://www.rgbstock.com
Official monkees youtube channel for Video.
colors: https://www.coolers.co
        Flat UI pallette V1

<h3>Acknowledgements</h3>

Media Queries for various device sizing were implemented from previous Code Institute modules and example designs.
Bootstrap carousel was added with guidance from youtube creator <Sonar Systems>  https://www.youtube.com/watch?v=n8ItscKLf7s
W3 Schools code used .
Iframe for youtube video sourced from the main Youtube page.

MIT License

Copyright (c) [2019] [David Walsh]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


