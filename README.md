# Bitpay Theme

A theme for ghost blogging platform. Forked from Casper.

## When Writing posts

There are a few elements you can put in the markup. For example this can go in the markup and gives us a big ole button to hit for blog posts that need a definite call to action.
`<a href="http://bitcore.io/playground"><button class="cta-button" >Go to the Bitcore Playground</button></a>`

## Installation

Start your ghost instance and run
`npm start`

Log into your ghost Dashboard > Settings - General

Choose `BitPay` from the theme dropdown

# Development

As of now, you must restart ghost everytime a `.hbs` file is changed.

Command that watches Sass Files
`sass --watch assets/sass/input.scss:assets/css/output.css`
