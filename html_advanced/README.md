# This is a Readme for the HTML_Advanced Project
## In this project we will be working with HTML

# Author - Ethan Zalta

## There are 41 tasks in this projectand 2 bonus tasks


## **Task 0**
* Create your first HTML file 0-index.html with:
    * Add the doctype on the first line (without any comment)
    * After the doctype, open and close a html tag
    * Add the language tag, specify English for ISO language code and add the direction tag (ltr or rtl) on the html tag.
    * Open y`our file in your browser (the page should be blank)

## **Task 1**
* Copy the content of 0-index.html into 1-index.html

* Create the head and body sections

    * inside the html tag, create the head and body tags (empty) in this order

## **Task 2**
* Copy the content of 1-index.html into 2-index.html
* Viewport:
    * add a meta tag inside the head:
        * add an attribute name on the tag and specify that it is the meta viewport
        * add the key width with the value device-width
        * add the key initial-scale with the value 1.0
        * add the key viewport-fit with the value cover

* Title:
    * add the title tag just after the meta viewport with value: Homepage - Techium

* Description:
    * add a meta tag inside the head section
        * add an attribute name on the tag and specify that is the meta description
        * add another attribute called content
        * add the following description: Techium is a digital agency

* Favicons:
    * download the image above to use as a favicon
    * Use the tool at https://realfavicongenerator.net/ to generate all the favicon formats
    * take the favicon.ico and favicon.png and place these at the root of your project directory, so that it is siblings with your [0-9]+-index.html files.
    * inside the head, create 2 link tags with these 3 attributes: rel, type, and href.
        * the first link tag:
            * rel: icon
            * type: image/x-icon
            * href: ./favicon.ico
        * the second link tag:
            * rel: icon
            * type: image/png
            * href: ./favicon.png

## **Task 3**
* Copy the content of 2-index.html into 3-index.html

* Header:
    * create the header of your page between the open and close body tag
    * put the text Header inside the header

* Main:
    * create the main tag after the header tag
        * put the text Main content inside your main tags

* Footer:
    * create the footer tag after the main tag
        * put the text Footer inside the footer tags

## **Task 4**
* Copy the contents of 3-index.html into article.html

    * change the <title> to put: Article - Techium
    * inside the main tags
        * after the text, create the aside tags with text Aside

## **Task 5**
* Copy the content of 3-index.html into 5-index.html

    * inside your <main> section
        * remove the text in main, create these sections:
            1. create first section and put the text Hero section inside
            2. create second section and put the text Services section inside
            3. create third section and put the text Works section inside
            4. create fourth section and put the text About section inside
            5. create fifth section and put the text Latest news section inside
            6. create sixth section and put the text Testimonials section inside
            7. create seventh section and put the text Contact section inside

## **Task 6**
* Copy the content of 5-index.html into 6-index.html

* Work articles:
    * inside the section Works section
        * add 3 article tags
            * inside each article write Work # where the hashtag will be the ordered number (1, 2, or 3)

* News articles:
    * inside the section Latest news section
        * add 3 article tags
            * inside each article write Article # where the hashtag will be the ordered number (1, 2, or 3)

* Testimonial articles:
    * inside the section Testimonials section
        * add 3 article tags
             * inside each article write Testimonial # where the hashtag will be the ordered number (1, 2, or 3)

## **Task 7**
* Copy the content of 6-index.html into 7-index.html

    * remove the Header text inside the <header>
    * create the nav tag inside the header tag
        * it should remain empty for now

## **Task 8**
* Copy the content of 7-index.html into 8-index.html

    * create the level 1 heading inside your main before your sections
        * put text Homepage in your heading tag

## **Task 9**
* Copy the content of 8-index.html into 9-index.html

    * in the section tag with the the text Hero section, remove the text and create a level 2 heading with text We help you build your brand!
    * in the section tag with the the text Services section, remove the text and create a level 2 heading with text Services
    * in the section tag with the the text Works section, remove the text and create a level 2 heading with text Works
    * in the section tag with the the text About section, remove the text and create a level 2 heading with text About Us
    * in the section tag with the the text Latest news section, remove the text and create a level 2 heading with text Latest news
    * in the section tag with the the text Testimonials section, remove the text and create a level 2 heading with text Testimonials
    * in the section tag with the the text Contact section, remove the text and create a level 2 heading with text Contact

## **Task 10**
* Copy the content of 9-index.html into 10-index.html

* Services headings:
    * Inside the section containing the h2 heading Services, add these elements right after the h2:
        * create a level 3 heading with text Design & Concept
        * create a level 3 heading with text Digital Strategy
        * create a level 3 heading with text Content Strategy
        * create a level 3 heading with text UX Design
        * create a level 3 heading with text Web Development
        * create a level 3 heading with text Social Media

* Works headings:
    * Inside the section containing the h2 heading Works:
        * in the first article, replace the text with a level 3 heading with text Interior Design
        * in the second article, replace the text with a level 3 heading with text Web Development
        * in the third article, replace the text with a level 3 heading with text Personal Brand

* About Us headings:
    * Inside the section containing the h2 heading About Us, after the h2 heading, create these elements in this order:
        * a level 3 heading with text Who are we
        * a level 3 heading with text Our culture
        * a level 3 heading with text How we work

* Latest news headings:
    * Inside the section containing the h2 heading Latest news:
        * in the first article replace the text with a level 3 heading with text Hoc loco tenere se Triarius non potuit.
        * in the second article replace the text with a level 3 heading with text Ut alios omittam, hunc appello, quem ille unum secutus est.
        * in the third article replace the text with a level 3 heading with text Bestiarum vero nullum iudicium puto.

## **Task 11**
* Copy the content of 3-index.html into 11-styleguide.html

    * change the title to Styleguide - Techium
    * remove the text from header, main, and footer
    * create a new <section> inside your main tag
        * create a header in this section
            * in the header add a level 2 heading with text Headings
        * after the header:
            * add a level 1 heading with text Heading level 1
            * add a level 2 heading with text Heading level 2
            * add a level 3 heading with text Heading level 3
            * add a level 4 heading with text Heading level 4
            * add a level 5 heading with text Heading level 5
            * add a level 6 heading with text Heading level 6

## **Task 12**
* Copy the content of 10-index.html into 12-index.html
* Add three paragraphs to About me,
* Add three paragraphs to Latest news
* Add paragraph to Contact
* Add additions paragraphs below Services, Works, About Us, Testimonials, Contact

## **Task 13**
* Copy the contents of 11-styleguide.html into 13-styleguide.html
    * After the existing section containing Headings, create a new section in main
        * in this section create a header
            * Inside the header, create a level 2 heading with text Paragraph
        * after the header add a level 2 heading with text Heading with a subtitle
        * after the level 2 heading, add a paragraph with text This is my subtitle
        * after the last paragraph, add another paragraph with text: Nunc~


## **Task 14**
* Copy the contents of 12-index.html into 14-index.html
* In the very first <header>,
    * before the nav, create a span with the text Techium


## **Task 15**
* Copy the contents of 14-index.html into 15-index.html
    * Wrap the contents of the header element with a div
    * Wrap the contents of all section elements with a div
    * Finally, wrap the contents of the <footer> tag with a div

## **Task 16**
* Copy the contents of 15-index.html into 16-index.html

    * in the div in the Services section
        * create a header tag that wraps the h2 and the p
        * create a div sibling to the header that wraps the rest of the content
    * in the div in the Works section
        * create a header tag that wraps the h2 and the p
        * create a div sibling to the header that wraps the rest of the content
    * in the div in the About Us section
        * create a header tag that wraps the h2 and the p
        * create a div sibling to the header that wraps the rest of the content
    * in the div in the Latest news section
    * create a header tag that wraps the h2
    * create a div sibling to the header that wraps the rest of the content
    * in the div in the Testimonials section
        * create a header tag that wraps the h2 and the p
        * create a div sibling to the header that wraps the rest of the content
    * in the div in the Contact section
        * create a header tag that wraps the h2 and the first p
        * create a div sibling to the header that wraps the rest of the content

## **Task 17**
* Copy the content of 16-index.html into 17-index.html

    * before the header add a line break and a comment saying Header to help with scanning your code
    * before the main add a line break and a comment saying Main to help with scanning your code
    * before the footer add a line break and a comment saying Footer to help with scanning your code
    * before the Hero section add a line break and a comment saying Hero section
    * before the Services section add a line break and a comment saying Services section
    * before the Works section add a line break and a comment saying Works section
    * before the About Us section add a line break and a comment saying About Us section
    * before the Latest news section add a line break and a comment saying Latest news section
    * before the Testimonials section add a line break and a comment saying Testimonials section
    * before the Contact section add a line break and a comment saying Contact section


## **Task 18**
* Copy the content of 17-index.html into 18-index.html

    * in the header, wrap the span with a link that redirects to the page at the root of your folder (/)
    * wrap the link with a div


## **Task 19**
* Copy the content of 18-index.html into about.html, latest_news.html and contact.html

    * change the title of about.html to replace Homepage with About
    * change the title of latest_news.html to replace Homepage with Latest news
    * change the title of contact.html to replace Homepage with Contact


## **Task 20**
* Copy the content of 18-index.html into 20-index.html

    * in your nav tags
        * create a link to / with the text Home
        * create an anchor to services with the text Services
        * create an anchor to works with the text Works
        * create an anchor to about with the text About
        * create an anchor to latest_news with the text Latest news
        * create an anchor to testimonials with the text Testimonials
        * create an anchor to contact with the text Contact



## **Task 21**
* Copy the content of 20-index.html into 21-index.html
    * in the div in the footer
        * remove any text you have
        * create a link to https://www.facebook.com/HolbertonSchool/ with the text Facebook
        * create a link to https://twitter.com/holbertonschool with the text Twitter
        * create a link to https://www.instagram.com/holbertonschool/ with the text Instagram

## **Task 22**
* Copy the content of 21-index.html into 22-index.html
    * in the Hero section, after the heading
        * create a link to # with the text Get started
    * in the About Us section, after the div containing the level 3 headings and paragraphs
        * create a link to about.html with the text Learn more about us
    * in the Contact section, after the div containing the paragraph
        * create a link to contact.html with text Get in touch

## **Task 23**
* Copy the content of 22-index.html into 23-index.html

    * in the Services section
        * in each level 3 heading, create a link to # around the text already in the heading
    * in the Works section
        * in each level 3 heading, create a link to # around the text already in the heading
    * in the Latest news section
        * in each level 3 heading, create a link to # around the text already in the heading

## **Task 24**
* Copy the content of 23-index.html into 24-index.html

    * in the nav
        * create an unordered list, put each anchor tag (Home, Services, Works, …) as an individual list item
    * in the div in the footer
        * create an unordered list and put each anchor tag (Facebook, Twitter, …) as an individual list item

## **Task 25**
* Copy the content of 24-index.html into 25-index.html

    * inside the footer, after the div
        * create a new div
        * in the new div create an unordered list with the following links:
            1. link to # with text Terms of Use
            2. link to # with text Privacy Policy
            3. link to # with text Cookie Policy

## **Task 26**
* Copy the content of 13-styleguide.html into 26-styleguide.html

* Example of unordered list:
    * inside main after Paragraph section, add :
        * a new line and a comment with text Lists
        * after, create a new section with inside:
            * create a header with inside a level 2 heading with the text Lists
            * after the new header, create a div with inside:
                * a level 3 heading with text Unordered
                    * under it, add an unordered list with these items: Dolor pulvinar etiam magna etiam., Sagittis adipiscing lorem eleifend., Felis enim feugiat dolore viverra.

* Example of ordered list:
    * after previous unordered list, in the same div
        * add a level 3 heading with text Ordered
                * add an ordered list with these items:
                    1. Dolor pulvinar etiam magna etiam.
                    2. Sagittis adipiscing lorem eleifend.
                    3. Felis enim feugiat dolore viverra.

* Example of definition list:
    * after previous ordered list, in the same div
        * add a heading level 3 with text Definition
        * add a definition list with these items:
            1. Term: Definition List title, Definition: Definition text.
            2. Term: Startup, Definition: A startup company or startup is a company or temporary organization designed to search for a repeatable and scalable business model.
            3. Term: Water, Definition: A colorless, transparent, odorless liquid that forms the seas, lakes, rivers, and rain and is the basis of the fluids of living organisms.

## **Task 27**
* Copy the content of 25-index.html into 27-index.html

    * in the footer between the two divs:
        * add a horizontal rule
        * after the horizontal rule add a paragraph with text © 2020 Techium, made with ♥ by students at Holberton School.

## **Task 28**
* Copy the content of 26-styleguide.html into 28-styleguide.html

    * in main after Lists section
        * add a new line and a comment with the text Horizontal rule
        * create a new section
            * create a header and inside it add a level 2 heading with the text Horizontal rule
            * after the header create a div and put a horizontal rule in it

## **Task 29**
* Copy the content of 27-index.html into 29-index.html

    * in the Testimonials section
        * in the first article
            * replace the text with a blockquote with text I am completely blown away. Thanks to Techium, we've just launched our 5th website! and cite author Yuri Y.
    * in the second article
        * replace the text with a blockquote with text Thank you so much for your help. Techium company is awesome! and cite author Dorrie S.
    * in the third article
        * replace the text with a blockquote with text I love your system. Definitely worth the investment. I'd be lost without Techium company. and cite author Sven H.

## **Task 30**
* Copy the content of 28-styleguide.html into 30-styleguide.html

* Example of inline quote:
    * inside main after Horizontal rule section
        * add a new line and a comment with text Blockquotes
        * create a new section
            * in the section create a header, in the header create a level 2 heading with text Blockquotes
            * after the header, create a div
                * in the div add a level 3 heading with the text Inline quote
                * add an inline quote with the text Stay hungry. Stay foolish.

* Example of blockquote:
    * after the inline quote div, create another div
        * in the new div add a level 3 heading with the text Blockquote
        * add a multiline quote with the text I will be the leader of a company

## **Task 31**
* Copy the content of 29-index.html into 31-index.html

    * in the footer
        * right after open footer tag, put the following address: 234 Washington Street (line-break) Urbana, Illinois
    * in the Latest news section
        * in the first article, after the last paragraph, add the author name in small print: By Kelly D.
        * in the second article, after the last paragraph, add the author name in small print: By William A.
        * in the third article, after the last paragraph, add the author name in small print: By Frances J.

## **Task 32**
* Copy the content of 30-styleguide.html into 32-styleguide.html

    * inside main after the Blockquotes section
        * add a new line and a comment with text Typography
        * create a new section
            * in the section create a header and inside it add a level 2 heading with the text Typography
            * after the header create a div, inside the div add this text with the correct HTML tag: 320 Stewart Avenue, Unit 12 (line break) New York City NY 10001, the city, state, and postal code should be on a separate line
            * create another div, in the new div nest this code block using the pre HTML tag:
            * create another div, in the new div add this paragraph of text with the correct HTML tag: Curabitur sit 

## **Task 33**
* Copy the content of 32-styleguide.html into 33-styleguide.html

    * inside main after Typography section
        * add a new line and a comment with text Table
        * create a new section
            * in the section create a header, in the header add a level 2 heading with the text Table
            * after the header, create a table, reproduce in HTML the visual below

## **Task 34**
* Copy the content of 33-styleguide.html into 34-styleguide.html
    * in main tag after Table section
        * add a new line and a comment with text Details
        * create a new section
            * create a header, in the header add a level 2 heading with the text Details
            * after the header create a div
                * in the div add a level 3 heading with text Default
                * add a details element and specify Show/Hide me in the summary
                * add this text after the summary: Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.
            * create another div
                * add a level 3 heading with text Open
                * add a details element that is open by default and specify Always open in the summary
                * add this text after the summary: Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.

## **Task 35**
* Copy the content of 31-index.html into 35-index.html
    * in header
        * find the span with the name of the website
        * replace it with the image above
        * make sure the image is in the same directory as all of your other files and that the file name is logo-black.png
        * alt: Techium logo
        * don’t forget to specify width of 160 and height of 40
    * in footer, after the opening tag and before the address
        * insert the logo image
        * alt: Techium logo
        * don’t forget to specify the width and height (same as in header)

## **Task 36**
* Copy the content of 35-index.html into 36-index.html

* You can use image generators to get images for this task. For avatar images you can download them on UI Faces. Just make sure you rename your images to match the task requirements.

* Add three images in the Works section:
    * in the Works section
        * before the first level 3 heading create a div
            * add images/pic-work-01.jpg inside the div
            * alt: empty
        * before the second level 3 heading create a div
            * add images/pic-work-02.jpg inside the div
            * alt: empty
        * before the third level 3 heading create a div
            * add images/pic-work-03.jpg inside the div
            * alt: empty

* Add one image in the About Us section:
    * in the About Us section before the first level 3 heading inside the div
        * add the image images/pic-about-us.jpg
            * alt: empty
            * width: 460
            * height: 447

* Add three images in the Latest news section:
    * in the Latest news section
        * in the first article, before the first paragraph, create a div
            * in the div add the image images/pic-blog-01.jpg
            * alt: empty
            * width: 305
            * height: 205
        * in the second article, before the first paragraph, create a div
            * in the div add the image images/pic-blog-02.jpg
            * alt: empty
            * width: 305
            * height: 205
        * in the third article, before the first paragraph, create a div
            * in the div add the image images/pic-blog-03.jpg
            * alt: empty
            * width: 305
            * height: 205

* Add three images in the Testimonials section:
    * in the Testimonials section
        * in the first article before the quote, add the image images/pic-person-01.jpg
            * alt: Yuri Y. avatar
            * width: 100px
            * height: 100px
        * in the second article before the quote, add the image images/pic-person-02.jpg
            * alt: Dorrie S. avatar
            * width: 100px
            * height: 100px
        * in the third article before the quote, add the image images/pic-person-03.jpg
            * alt: Sven H. avatar
            * width: 100px
            * height: 100px

## **Task 37**
* Copy the content of 36-index.html into index.html (the final file!)

    * inside the footer

        * replace the text Facebook with the SVG icon code and add width of 25px and height of 25px to the SVG tag:
        * replace the text Twitter with the SVG icon code and add width of 25px and height of 25px to the SVG tag:
        * replace the text Instagram with the SVG icon code and add width of 25px and height of 25px to the SVG tag:



## **Task 38**
* Copy the content of 34-styleguide.html into 38-styleguide.html

    * in main after the Details section
        * add a new line and a comment with text Video
        * create a section
            * in the section create a header, in the header add a level 2 heading with the text Video
            * after the header add the following video: https://intranet-projects-files.s3.amazonaws.com/webstack/BigBuckBunny.mp4
            * add controls to the video
            * ensure that the video does a loop
            * display https://intranet-projects-files.s3.amazonaws.com/webstack/thumbnail.jpg when the video is downloading
            * provide an alternative text: Sorry, your browser doesn't support HTML5 video

## **Task 39**
* Copy the content of 38-styleguide.html into 39-styleguide.html

    * in main after Video section
        * add a new line and a comment with text Audio
        * create a section
            * in the section create a header, in the header add a level 2 heading with the text Audio
            * after the header add the following audio file: https://intranet-projects-files.s3.amazonaws.com/webstack/TroubleChapter8_64kb.mp3
            * add controls to the audio player
            * provide an alternative text: Sorry, your browser doesn't support audio element

## **Task 40**
* Copy the content of 39-styleguide.html into styleguide.html

    * in main after the Audio section
        * add a new line and a comment with text Iframe
        * create a section
            * in the section create a header, in the header add a level 2 heading with the text Iframe
            * after the header add a div
                * inside the div, create an iframe
                    * title: Holberton School
                    * width: 350px
                    * height: 200px
                    * source: https://www.youtube.com/embed/41N6bKO-NVI
                    * fallback text: Holberton Sally
