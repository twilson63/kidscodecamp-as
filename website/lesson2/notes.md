# Introduction

Now that all the students have created their first web page, we need to walk
through the process of creating a directory for the list of super hero pages.

---

# What is an index or directory?

And index or directory is a collection of links, these links point to
the location of content.

---

# The most powerful feature of the internet

The internet enables computers to talk to each other and each computer has a location, that location has an address, just like you may have an address for your home. With the internet being so large, it is very hard to keep up with all the addresses, so we want to build a directory or index.

---

# Link

By using a tool called a hyperlink we can create an index of all the super hero pages you have built, this will make it easy for us as a class to connect the super hero's together in a hall of justice.

---

# How to build a link

In HTML, we use an element called an Anchor, just like speaking languages have nouns, verbs, adjectives. Computer languages have semantics or patterns too. In html we call these semantics or keywords, elements.

---

# What is a HTML element?

A HTML element is a keyword or command that instructs the program to present data in a specific way. In the lesson before, we used the heading1 element. `h1` and inorder to separate that element from the actual data, we used a tag syntax. `<h1>` + data + `</h1>`. This tag syntax creates a wrapper around the data.

---

# Creating directory or hall of justice

In creating a directory we need to use more than just the heading1 element, we need to use the following elements (h1, a, ul, li)

But don't worry, we will explain these in more detail in future lessons.

---

# Exercise Demo

In this demo, go to one of the editors and create a new web page, in this web page add the following:

``` html
<h1>Hall of Justice</h1>
<ul>
  <li>
    <a href="[link to super hero]">[Super Hero Name]</a>
  </li>
  <!-- repeat for all super heros in the class -->
</ul>
```

Make this an interactive exercise, that you enage each student and have them provide you a name of their super hero, and walk through the process of building a url.

---

# Exercise Demo part 2

Demonstrate how to add a re-link back to the hall of justice from your super hero page.

``` html
<h1>My Super Hero</h1>
<a href="[link to all of justice]">Hall of Justice</a>
```

# Exercise

Have each student open up their super hero page and edit their page with a new link. You may need to help them out with creating the address.
