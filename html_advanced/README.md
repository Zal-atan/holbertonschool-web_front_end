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



## **Task 13**
