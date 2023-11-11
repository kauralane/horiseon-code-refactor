# Horiseon Code Refactor
## Description
This application is an accessible Horiseon home page. I started with Horiseon’s original code and refactored it to meet certain accessibility standards, of course without changing how the page looks or functions overall. Accessibility is rightly extremely important, to enable those with assistive technologies to access an application. And that’s not to mention the SEO benefits.

I changed the code so that the application is now made up of solely semantic HTML elements; 'span' and 'div' do not feature anywhere within it! All the corresponding CSS selectors have also been changed to match their new semantic HTML elements. Alt attributes have been added for every image and icon, and headings run in the correct order. 

Along the way I’ve also tidied some things up in this codebase; for example in the CSS sheet I’ve consolidated multiple classes with the same styles to make the code more concise. 

One of the 3 nav links was broken so I’ve also fixed that. This was a fun lesson as I accidentally broke all 3 links without even realising. I thought I’d nearly finished the work, and did a final comparison with the original site, and only then did I realise I’d broken 3 links! I had to do a side-by-side comparison of the original code and my new accessible code, and eventually realised I had accidentally deleted 2 ID’s which were key to the functioning of the links. I learnt a good lesson there: when refactoring, never take your eye off the original code!

Deployed application:

## Installation
None.

## Usage
This application is simple to use, and can be viewed and read with assistive technologies. There are 3 links to interact with in the header, and these will take you to the corresponding section of the page.

## Credits
Code base: Horiseon Social Solution Services, Inc.

## License
Licensed under the MIT License.