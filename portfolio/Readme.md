Requirements:
1. 4 images
2. titel (h1,h2)
3. regular paragraph
4. logo
https://www.diigo.com/outliner/fimj2p/Udacity-Portfolio-Project?key=76qgm0v3vj

https://www.youtube.com/watch?v=HmYPqwSefoA

Think about the html code we need to write to see this structure. From there we break it down and think of how we're supposed to order the code, and start from a mobile first perspective and work our way up. 

What do we see in mockup?
3 rows:
row = html container (div tag)

Row 1: (Basics of html/css) Header
This is a block level element, which takes 100% of the parent container. This container has 2 child elements the logo, and the container which holds 2 more child elements, the name, and title.

 First Row: Div with class of logo, and another div with class of header. Every page should have a single h1 tag. So the name would be a h1 tag and the title tag can be a paragraph tag and we style it to change font. 

 So when we get a markup we need to see this as code first, keep breaking it down. 

In MAIN:

 Second Row: (Responsive images)
 We see a giant image. 
 The Rectangle is very wide, which can be an issue when making it responsive
 . This is an example of a need for responsive images. This would look terrible on mobile. 

 Row 3: flexbox
 if we didn't change anything they'd just stack on each other on a mobile phone.
text element (h2)
3 images side by side (flexbox)
3 div's to hold each element.
Each div has a image that takes up 100% width, and 2 text element tags. 

Repeat ^ 3 times.


placeholder.com

html:
1. header
2. main class
3. section of work which includes Div's 
4. each div needs a class, img tag, h,p,and href

css:
basic styling
media queries