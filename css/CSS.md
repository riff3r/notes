# HTML & CSS

    html5 tag list
    https://www.tutorialrepublic.com/html-reference/html5-tags.php

    css propertise
    https://www.tutorialrepublic.com/css-reference/css3-properties.php

### Typography

### SANS-SERIF FONT – Google Fonts, Font Squirrel - Modern Design

    1.	Inter
    2.	Open Sans
    3.	Roboto
    4.	Montserrat
    5.	Work Sans
    6.	Lato

### SERIF – Traditional / Classical Design

    1.	Merriweather
    2.	Aleo
    3.	Playfair Display
    4.	Cormorant
    5.	Cardo
    6.	Lora

### Font Size

    1.	Limit Choices! – Use “Type Scale”
    2.	Normal Text should be 16px – 32px
    3.	Long Text (Like blog), Try 20px or even bigger
    4.	Headline – Can be 50px+ and bold (600+)
    5.	For any text never use font weight under 400

### Good Reading Experience

    1.	Less than 75 characters per line
    2.	For normal size, use line height 1.5-2
    3.	For Larger size, Use line height below 1.5
    4.	Decrease letter spacing in headlines
    5.	All caps for short titles. Make them small and bold and increase letter-spacing

### SANS-SERIF FONT – Google Fonts, Font Squirrel - Modern Design

    1. Inter
    2. Open Sans
    3. Roboto
    4. Montserrat
    5. Work Sans
    6. Lato

### SERIF – Traditional / Classical Design

    1. Merriweather
    2. Aleo
    3. Playfair Display
    4. Cormorant
    5. Cardo
    6. Lora

### Background-Color, Height, Width, Font, CSS Measuring Units

### Three pillars of good HTML and CSS

    1. Responsive Design
    2. Maintainable and Scalable
    3. Web performance

### Margin

    margin: 50px 20px 50px;
    margin: top (left-right) Bottom;

### Padding

    padding: 50px 20px 50px;
    padding: top (left-right) Bottom;

### CSS Box Model

### HTML Block and Inline Elements

    Block-level Elements

        - A block-level element always starts on a new line.

        - A block-level element always takes up the full width available (stretches out to the left and right as far as it can).

        - A block level element has a top and a bottom margin, whereas an inline element does not.

    Inline Elements

        - An inline element does not start on a new line.

        - An inline element only takes up as much width as necessary.

        - This is a <span> element inside a paragraph.

### Center Anything with CSS

    Resource - https://www.freecodecamp.org/news/how-to-center-anything-with-css-align-a-div-text-and-more/

    - How to Center?

    1. margin: 0 auto;

    2. display: flex; justify-content: center;

    3. How to Center Vertically with Flexbox?

    .container {
    /_ Center vertically _/
    display: flex;
    align-items: center;
    }

    4. How to Center a Div Vertically and Horizontally with Transform and Translate?

    .container {
    position: relative;
    }

    .child {
    /_ Center vertically and horizontally _/
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    }

    5. How to Center a Div Vertically and Horizontally with Flexbox?

    .container {
    /_ Center vertically and horizontally _/
    display: flex;
    justify-content: center;
    align-items: center;
    }

### Box-Shadow

    Resource - https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow

### Border

    Resource - https://css-tricks.com/gradient-borders-in-css/

    .border-gradient {
    border: 10px solid;
    border-image-slice: 1;
    border-width: 5px;
    }

    .border-gradient-purple {
    border-image-source: linear-gradient(to left, #743ad5, #d53a9d);
    }

    or

    border-image: linear-gradient(to bottom, red, rgba(0, 0, 0, 0)) 1 100%;

### Pseudo class & Element

    Resources -
    https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors/Pseudo-classes_and_pseudo-elements
    Details with example - https://www.smashingmagazine.com/2016/05/an-ultimate-guide-to-css-pseudo-classes-and-pseudo-elements/

    pseudo-classes are always preceded by a colon (:)

    pseudo-elements are always preceded by double colon (::)

### HTML Table

    <table></table>
    <thead></thead>
    <tbody></tbody> - Table Body
    <th></th>       - Table Head
    <tr></tr>       - Table Row
    <td></td>       - Table Data

    Example -
    <table>
        <thead>
            <tr>
                <th></th>
            </tr>
        </thead>

        <tbody>
            <tr>
                <td>1</td>
            </tr>
        </tbody>
    </table>

    table, th, td {
    border: 1px solid lightgray;
    border-collapse: collapse;
    padding: 5px 20px;
    }

### HTML Form

    Fieldset Legend

    Radio Button
        - Use label for input.
        - Use unique id in input
        - Use Same name for

    EXAMPLE -
    <form action="">
      <label for="lol"> <input type="radio" id="lol" name="moba" /> LOL </label>
      <label for="DOTA"> <input type="radio" id="DOTA" name="moba" /> DOTA </label>
    </form>

    Checkbox

    button  type - submit, reset

### Nav

    Nested Navigation -
    nav > ul > li:hover > ul{
        display: block;
    }

### HTML Tags

    Resource - https://web.programming-hero.com/web-5/video/web-5-6-8-all-html-tags-everything-you-need-to-know-about-html

### HTML Attribute Reference

    https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes
    https://www.w3schools.com/tags/ref_attributes.asp

### More CSS, Icon, CSS3 Animation

    css animation library
    https://css-tricks.com/css-animation-libraries/
    https://animate.style/


    visibility: hidden - Content not displaying in html but taken place / space.
    display: none - Totally invisible

    overflow: visible -
    overflow: Hidden - hide the rest of content
    overflow: Scroll - Create scroll bar in x and y axis
    overflow-x, overflow-y Use if needed

### text-overflow: ellipsis

    // Parent Div
    .mini-mini {
    width: 300px;
    border: 3px solid indianred;
    }

    // text overflow
    .short-text {
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
    }

### Transform

    /* Multiple function values */
    transform: translate(100px, 100px) scale(0.5) rotate(30deg);
    transform: perspective(500px) translate(10px, 0, 20px) rotateY(3deg);

    https://www.w3schools.com/cssref/css3_pr_transform.asp
    https://developer.mozilla.org/en-US/docs/Web/CSS/transform

### Transition

    transition: <property> <duration> <timing-function> <delay>;

    Multiple property with coma - transition: width 1s, transform 1s;

    Resource - https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Transitions/Using_CSS_transitions

### Animation

    animation: name duration timing-function delay iteration-count direction fill-mode;

    animation: sliding 1s ease-in-out 0.5s infinite alternate;

    https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Animations/Using_CSS_animations

### Gradient Text Color

    1. background: linear-gradient(left, #38d39f, #38a4d3)
    2. background-clip: text; / -webkit-background-clip: text;

    3. -webkit-text-fill-color: transparent;

### Image ratio, fixed height and width

    If fixed height and width given then use to image tag then add
    object-fit: cover;

### Flexbox

    https://css-tricks.com/snippets/css/a-guide-to-flexbox/

    display: flex;
    flex-start | flex-end | center | space-between | space-around | space-evenly | start | end | left | right ... + safe | unsafe;

    align-item: stretch; // stretch to fill the container
    flex-grow: 1; // This defines the ability for a flex item to grow if necessary
    flex-wrap: wrap; // flex items will wrap onto multiple lines, from top to bottom.
    flex-flow: column wrap; // flex-direction and flex-wrap

    flex-wrap: wrap;  // By default, flex items will all try to fit onto one line. You can change that and allow the items to wrap as needed with this property.

    order:1; // the order property controls the order in which they appear in the flex container.

### Grid

    https://css-tricks.com/snippets/css/complete-guide-grid/
    https://www.viget.com/articles/getting-started-with-css-grid-part-1/
    https://www.viget.com/articles/getting-started-with-css-grid-three-part-2/

        display: grid;
        grid-template-columns: 1fr 1fr 1fr 1fr;
        grid-template-columns: repeat(4, 1fr);
        grid-template-columns: repeat(4, 1fr) 2fr;
        grid-gap: 20px;

# UI UX DeBug

### Rules to follow as best practice while designing a website

    1. Website Purpose - Simplicity
    2. Color
    3. Alignment
    4. White Space
    5. Typography

### Design Resources, figma edit and design secrets

    search - figma resources

### CSS specificity, style priority and !important

    https://css-tricks.com/specifics-on-css-specificity/

    https://developer.mozilla.org/en-US/docs/Web/CSS/Specificity

    CSS Specificity

    tag > class > id > !important (Do not use)

### CSS Custom property and use var, calc

    :root{
        --main-color: blue;
    }

    body{
        color: var(--main-color)
    }

### Advanced selectors

    https://css-tricks.com/almanac/selectors/a/attribute/

    Attribute Selector. Ex -
    input[type="text"]{
        width: 200px;
    }

### BEM

    https://css-tricks.com/bem-101/


    airbnb css style guides

    https://github.com/airbnb/css
    https://cssguidelin.es/
