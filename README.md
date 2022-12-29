# bayy

A simple landing page for a fictitious app called bayy. Bayy is an AI chat app that listens and talks back to the user. The theme and concept was inspired by JOI from the movie Bladerunner 2049. JOI is an AI companion/hologram that Joe or Officer K uses.

The site is fully responsive and mobile friendly using Bootstrap 5. Break points occur at a medium viewing size which is < 768px at which point a menu icon appears and smoothly drops down for additional links in navigation.

The buttons are not bootstrap related because I wanted to try small animations/color gradients. The top right of the button is kept at a sharp 90 degree radius but smooths out to full on mouse hover. The text inside of the button also changes to blue on mouse hover.

For the logo I chose what looks like a lowercase a. I feel like a logo like this could be easily branded and is memorable. It’s been converted to SVG format to allow for high definition on high res screens as well as low res. The back-ground is also the logo except with an opacity filter I added using inkscape.

For bayy herself I used mid journey bot to create an entirely new and unique mascot. I wanted to create a mascot that looked real but not too real since it’s still just an AI bot. The prompt I used to generate her was a mixture of my favorite citypop artist Mariya Takeuchi, beautiful, retrowave, and creative. I ran into a few issues with bayy's positioning because the desktop view has absolute but needed to be relative on mobile. I couldn't find a solution bootstrap related so I incorporated a media query that changes the property based on what platform the user is on. I decided to use a retrowave prompt so it would fit better with the pink and magenta theme. The final product came out better than expected. After getting the images I simply use gimp to grab the selected model while turning the background transparent. A few transparent selections inside of the hair and it was complete. 

## Technologies
![HTML](https://img.shields.io/badge/HTML-239120?style=for-the-badge&logo=html5&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white)
![Javascript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)
![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase)
![Gimp](https://img.shields.io/badge/Gimp-657D8B?style=for-the-badge&logo=gimp&logoColor=FFFFFF)
![Inkscape](https://img.shields.io/badge/Inkscape-000000?style=for-the-badge&logo=Inkscape&logoColor=white)

## Acknowledgements

 - [How to generate custom AI images](https://youtu.be/8xePoQ6ZuXI)


## Screenshots

![desktop](https://user-images.githubusercontent.com/48900828/209735577-96941dd5-bb84-4d10-bd5d-a3de02801391.PNG)

![mobile1](https://user-images.githubusercontent.com/48900828/209735582-b425f2e4-3491-4d1c-a2e2-ea39dd6da0e4.PNG)

![mobile2](https://user-images.githubusercontent.com/48900828/209735583-abbf1a58-abab-40b0-8c45-57af055c485d.PNG)

![facehero](https://user-images.githubusercontent.com/48900828/209735625-a4407597-427e-4214-a02b-28d4163f9469.png)


## Demo

https://bayy-5d17e.web.app/
