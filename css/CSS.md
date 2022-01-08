# CSS

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

### Pseudo class & Element

    Resources -
    https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors/Pseudo-classes_and_pseudo-elements
    Details with example - https://www.smashingmagazine.com/2016/05/an-ultimate-guide-to-css-pseudo-classes-and-pseudo-elements/

    pseudo-classes are always preceded by a colon (:).


    pseudo-elements are always preceded by double colon (::).
