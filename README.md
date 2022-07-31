# Horiseon-updated

This project took the original code from https://github.com/coding-boot-camp/urban-octo-telegram and made it more accessible, cleaned up the code, followed a proper  HTML semantic structure, and added clear and descriptive comments to describe the different sections and their uses. The CSS has been cleaned up and had a lot of the individual elements consolidated into one declaration block that had the same styles to reduce the repetitive code throughout the file. The CSS also got reorganized and divided into sections that correspond to the order found in the HTML. The HTML now follows a proper semantic structure so that there aren't just divs everywhere that don't help identify the element that is being coded. For example a div that was used for the footer was renamed to "<footer></footer>" to help easily identify what the element is supposed to be.

## Website
The link to the deployed application is: https://scarelite.github.io/Horiseon-updated/

## An example of consolidating the CSS look as follows:

Before: 

.benefit-lead h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-brand h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-cost h3 {
    margin-bottom: 10px;
    text-align: center;
}

After:

/* Applies to all of the h3's in the benefits section of the content section */
.right-column h3 {
    margin-bottom: 10px;
    text-align: center;
}

## Built With
*HTML
*CSS
