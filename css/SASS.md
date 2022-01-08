# SASS

### Let's Install Sass Locally

    1. Install node.js first.
    2. npm init - input info in cmd
    3. npm install node-sass --save-dev

    "scripts": {
        "compile:sass": "node-sass sass/main.scss css/style.css"
        "compile:sass": "node-sass sass/main.scss css/style.css -w" - To watch always
    }

    Terminal - npm run compile:sass

### Variables

$color-primary: #f9ed69; // Variable Starts with $
nav { background-color: $color-primary } // Example

### Nesting

    .nav{
        list-style: none;
        li{                                 // .nav li
            display: inline-block;

            &:first-child{                  // .nav li:first-child
                margin: 0;
            }

            a{                              // .nav li a
                text-decoration: none;
            }
        }
    }

### Mixin

    1) Basic implementation
    @mixin clearfix{                        // Mixin Declaration
        &::after{
            content: '';
            clear: both;
            display: table;
        }
    }

    .nav{
        @include clerfix;                   // Mixin Implementation
    }

    2) Implementation With Parameter
    @mixin style-link-text($color){                 // Mixin Declaration with parameter
        text-decoration: none;
        text-transform: uppercase;
        color: $color;
    }

    a:link{
        @include style-link-text($color-primary);           // Mixin Implementation with parameter
    }

    .btn-main:link{
        padding: 10px;
        @include style-link-text($color-primary);            // Mixin Implementation with parameter
    }

### Function

    @function divide($a, $b){               // Function needs a name,
        @return $a / $b;
    }

### Extends

    %btn-placeholder{
        Some CSS Code!!
    }

    Need to study again
