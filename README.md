# w6-aurum-grid

=======measurements========

dev tools test for grid responsiveness
at 1440px: 3 columns in collections
at 720px: 1 column in collections

gallery measurements
desktop mockup width: 1440px
gallery horizontal padding: 88px
gap between collections cards: 32px
minimum column width: 350px
calculated card width at 1440px: 400px
columns at 1440px: 3
columns at 720px: 1

collection gallery uses
grid-template-columng: repeat(auto-fit, minmax(350px, 1fr)); to allow number of columns to automatically adjust according to available space. 

footer uses grid-column: 1 / -1 span to extend content across both columns 

flexbox is used for header nav because its elements are arranged horizontally

grid is used for page structure, two column sections, collections gallery, and footer

=====Design Inventory======

this site uses Aurum brand palette developed for mtm1537
page background: #F2EBDC
text and footer background: #403E28
logo and button: #733B27
brand accent: #BFBA68B
brand accent 2: #A9C2D9

the desktop mockup uses The Seasons font for the Aurum wordmark logo, and Inter for remaining text

typography values
header wordmark: 48px
nav links: 20px
hero heading: 48px, line-height 1.2
hero para: 30px, line-height 1.4
explore collections button: 24px
about heading: 48px, line-height 1.2
about paragraphs: 30px, line-height 35px
collection labels: 30px, line-height 50px
footer wordmark: 48px
footer headings: 16px, line-height 20px
footer text and copyright: 16px, line-height 20px

<!-- Note! that The Seasons font is not yet dowloaded in my VS file. I wasn't made aware when the Flower Shop UX assignment was given out that this would be the one we are expected to code in this class, so it was all hypothetical at the time. Sorry. It is an Adobe Font, for reference. -->

spacing
main horizontal page padding: 88px
hero and about column gap: 48px
collection gallery gap: 32px
header vertical padding: 24px
hero top padding: 40px
hero bottom padding: 80px
about vertical padding: 80px
collection gallery vertical padding: 80px
footer top padding: 64px
footer bottom padding: 24px

======considering a sub grid========
Sub grid is not necessary because the cards don't contain uneven content that would require shared row alignment. 