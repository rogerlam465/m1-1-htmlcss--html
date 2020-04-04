# HTML Comprehension Questions


## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [ false ] `<div><span>hello</div></span>`

b) [ false ]

```html
<ul>
<li>one</li>
</ol>
```

c) [ true ] `<ul></ul><img/><ol><li>one</li></ol>`


## Q2 - What is a screenreader and why should we care about them?

_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_

Screenreaders are used for accessibility, specifically for individuals experiencing visual impairment. We should care about them firstly for legal reasons, i.e. the Canadian Accessibility Act (Bill C-81). And secondly and more importantly, we should care because we're decent people. I am, personally, likely to suffer strong visual impairment in the future, so I have a certain vested interest in promoting accessibility technologies.




## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation

Quite a lot of them, but I think the most pertinent one would be the <img> tag.

b) You want to create a website that lists all the art gallery websites in your city and links to their website.

<ol> or <ul>, with <li> inside, as well as <a href> for the specific links.

c) You want to sell designer hats. You need to receive orders from the user.

<form> and all its buddies.

## Q4 - Can a button be a child of a button? Explain your reasoning

Per the HTML reference document, a button's descendents cannot be a clickable element. Given that the button tag is used to display a clickable element, it shouldn't be possible.


## Q5 - What is the most generic tag you can use?

<div>


## Q6 - What do the following achronyms stand for?

a) `a`

Anchor

b) `ol`

Ordered List

c) `ul`

Unordered List

d) `li`

List

e) `tr`

Table Row

f) `th`

Table Heading

g) `td`

Table Data

## Q7 - Usually, `td` elements are children of what kind of elements?

Table rows.

## Q8 - What is the difference between td and th?

I know that a td is a table heading, and so it's usually the header of a column in the table, and as such is the first row of cells, but this seems like a semantic difference.

## Q9 - Which tag makes the text appear bigger: h1 or h3?

<h1>, if the CSS wills it so.

## Q10 - In which situation can you use self closing tags?

When the element has no children.

## Q11 - What is autofilling and why is it important?

Autofilling helps to simplify filling out data in a form. No one likes filling out their name and address for the four hundredth time.

## Q12 - Which attributes are always present in an img element?

src and alt

## Q13 - Which attribute is always present for an anchor tag?

href

