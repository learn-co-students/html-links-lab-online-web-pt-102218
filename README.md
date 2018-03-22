# HTML Links

### Cloning Down Your Repository

If you already have a personal repository:

* In the terminal, type `git clone https://github.com/<your_username_here>/exceptional-realty`
* A folder with your previous work will appear in the IDE file tree.

If you want to use the demo repository to follow along:

* In your terminal, type `git clone https://github.com/learn-co-curriculum/exceptional-realty-demo`.
* Type `cd exceptional-realty-demo` to navigate into the folder.
* Type `git fetch html-links`, the branch for this lesson.
* Type `git checkout html-links`, and you're good to go!

**Remember to use `httpserver` to live test your webpage**

<iframe width="640" height="480" src="//www.youtube.com/embed/_vZ7x_nFSl0?rel=0&modestbranding=1" frameborder="0" allowfullscreen></iframe>

<p><a href="https://www.youtube.com/watch?v=_vZ7x_nFSl0">Alternate video link</a>.</p>

### `<a href=''>`

The last thing we want to do for our basic site is to link all of our pages together. We create links using the _anchor link_ element, written as `<a>`. The `<a>` tag requires in an `href` attribute to tell the browser where we want the link to go to. We want to provide some navigation between pages, so just below our `<h1>` and `<h2>` tags, let's add an opening and closing `<a>` tag with the `href` attribute pointed to `index.html`. We then want to include the visible text that will become the clickable text on our page, so let's add in 'About' in between the opening and closing tags. Go ahead and add an additional `<a>` tag pointed to our 'New Properties,' 'Listings,' 'Market Report,' and 'Contact' HTML pages.

All of these links are internal, pointed to other parts of our site. If we wanted to add an external link to another website, we would provide a full URL path. Since we're building real estate website, we may want to provide a link to useful homebuyers' resources. So, for a final `<a>` tag, let's add a link to the Housing and Urban Development government website, at `http://hud.gov`, and include 'H.U.D.' as the link text.

Now, for this last link, we want to add one additional attribute, `target`. Setting this attribute to be `target='_blank'` will cause the browser to open a new tab when the link is clicked, whereas the previous links will change the current tab to change location. We've now got 6 links:

```
<a href="index.html">About</a>
<a href="new-properties.html">New Properties</a>
<a href="real-estate-listings.html">Listings</a>
<a href="market-report.html">Market Report</a>
<a href="contact.html">Contact</a>
<a href="http://hud.gov" target='_blank'>H.U.D.</a>
```

These links will act as our navigation, so go ahead and copy these, and paste them into each of your other HTML pages, just below your main headings. Some of our pages haven't been touched yet, so you may need to add some HTML and content to `contact.html` and `new-properties.html`.

Once we've got links on every page, test out the page in a browser tab. We should see now that we've got links going to each page of our site, and since they're on every HTML file we've created, we can navigate back and forth between our pages. If we click on the 'H.U.D.' link, we'll see that it opens a new tab instead.

Congratulations, you've just built a website! In some later lesson, we will return to Exceptional Realty to introduce additional HTML5 concepts. If you're working from your own repository, make sure to push to your remote repo so you can have your code accessible later.

```
git add .
git commit -m 'started real-estate-listings.html'
git push
```

<p data-visibility="hidden">View <a href="https://learn.co/lessons/html-links" title="HTML Links">HTML Links</a> on Learn.co and start learning to code for free.</p>
