<div>
  <h1>Auto margins</h1>
  <p>The Corpatech logo is the first list item in the list.</p>
<p>By giving it margin-right: auto, we gather up all of the extra space, and force it between the 1st and 2nd item.</p>
  <p>We can see what's going on here using the browser devtools:</p>
<br>
<img src="https://www.joshwcomeau.com/_next/image/?url=%2Fimages%2Finteractive-guide-to-flexbox%2Fmargin.png&w=828&q=75" width="500px" height="auto">
<p>There are lots of other ways we could have solved this problem: we could have grouped the navigation links in their own Flex container, or we could have grown the first list item with `flex-grow`. But personally, I love the auto-margins solution. We're treating the extra space as a resource, and deciding exactly where it should go.<p>
</div>
