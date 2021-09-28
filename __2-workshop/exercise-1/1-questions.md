# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [ false ] `<div><span>hello</div></span>`

Fixed: `<div><span>hello</span></div>

b) [ false  ]

```html
<ul>
<li>one</li>
</ol>
```
Fixed:
<ol>
    <li>one</li>
</ol>

c) [ false ] `<ul></ul><img/><ol><li>one</li></ol>`

Fixed: 
<ul>
    <li>
        <img/>
        <ol>
            <li>one</li>
        </ol>
    </li>
</ul>

## Q2 - What is a screenreader and why should we care about them?

_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_

Screen readers are incredibly important as it aids the visually impaired and makes web browsing more accessible.

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation

<img src=>

b) You want to create a website that lists all the art gallery websites in your city and links to their website.

ordered list. <ol></ol>

c) You want to sell designer hats. You need to receive orders from the user.

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning

No. A button is an "inline element". Inline elements should never store other elements.

## Q5 - What is the most generic tag you can use?

<div>

## Q6 - What do the following achronyms stand for?

a) `a` anchor tag

b) `ol` ordered list

c) `ul` unordered list

d) `li` list item

e) `tr` table row

f) `th` table head

g) `td` table cell

## Q7 - Usually, `td` elements are children of what kind of elements?

<td> is a child of the <tr> element

## Q8 - What is the difference between td and th?

th is for headers and td is a table cell. td contains the data for the table.

## Q9 - Which tag makes the text appear bigger: h1 or h3?

h1 is bigger than h3

## Q10 - In which situation can you use self closing tags?

When the element has no text to render between its tag like the "img" tag.

## Q11 - What is autofilling and why is it important?

autofilling is when the computer predicts the text you wish to write. It aids the user by speeding up the typing process. For example when typing in a website that you frequent, the browser will auto fill the rest of the information.

## Q12 - Which attributes are always present in an img element?

src=" "

## Q13 - Which attribute is always present for an anchor tag?

href=""