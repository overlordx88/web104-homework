## What do these spacing utility classes do to this headline?
`<h1 class="p-0 p-md-4 p-lg-0">Headline</h1>`

a. These classes will cancel each other out.

b. Since p-0 is first it will override all of the other classes. So the heading will have 0 padding on all breakpoints.

c. 0 padding on all breakpoints, 4 padding value on md breakpoint, then stop the padding from flowing to lg and xl.