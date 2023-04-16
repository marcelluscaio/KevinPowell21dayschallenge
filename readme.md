https://courses.kevinpowell.co/view/courses/conquering-responsive-layouts/274380-day-18-challenge-solution-mobile-first/793027-flexbox-challenge-4-solution-writing-the-html

Use of % for width

Use of max-width

Use of em and rem

Not use height. If necessary, use min-height or padding

Technique: instead of using lateral padding, set width to child.
It depends.

Flexbox: parent is flex, children are going to take minimum space as possible.

Flexbox row stretches the height of all item to be the same height. You can control that with "align items flex-start". Or you can wrap the item you don t want to stretch in a div. Or you can use align-self "flex-start"


- On challenge 6 I had trouble making the img the same size as the paragraph column. I could have used a div with the width 100% technique (as in the quality design section).
I calculated the width minus half the gap, instead.

on images, always set a max-width of 100%, so the image will never be bigger than its size (if you set width 100% it will fit the screen and get too big)
