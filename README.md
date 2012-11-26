# CSS Building Blocks #

**CSS Building Blocks** is a set of css stylesheets whose primary purpose is to provide vertical and horizontal "spacing helpers". They have no dependencies on existing frameworks such as the 960 grid system or twitter bootstrap, but they can become especially helpful when used in conjunction with one of these frameworks.

One simple scenario for using a "spacer" is to provide a specific and custom amount of height between two elements.

```html
<p>Here's my first paragraph.</p>
<div class="spacer50"></div>
<p>A 50px high spacer exists between my first and second paragraphs</p>.
```


Another example of their usage is to provide an element inside a grid framework such as twitter bootstrap that prevents a span from collapsing. (Note the use of the **spacer** classes).


```html
<div class="row">
   <div class="span4">
       <!-- empty has no content per se, but using spacer to prevent collapse -->
       <div class="spacer10"></div>
   </div>
   <div class="span4">
      <p>Some text...</p>
   </div>
   <div class="span4">
       <p>Some text...</p>
    </div>
</div>

<!-- Need a big space between the previous row and the next one, so use one of the bigger spacers -->

<div class="spacer30"></div>

<div class="row">
   <div class="span4">
       <!-- empty, but using spacer to prevent collapse -->
       <div class="spacer10"></div>
   </div>
   <div class="span4">
      <p>Some text...</p>
   </div>
   <div class="span4">
       <p>Some text...</p>
    </div>
</div>
```

More documentation to follow...