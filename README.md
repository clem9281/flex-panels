# flex-panels

Flex Panels problem from Javascript-30

### Fork and clone this repo, and run index.html on live server.

Check out the `index.html` and `index.css` files. You'll see there are 3 `<p>` tags inside each `.panel`, but the page is only showing the second `<p>`. This is because the first and second `<p>` tags are being transformed off the page. When we click each of the image panels, we want the panel to grow larger than it's neighbors, and we want the hidden text to animate into place. Fortunately, we have all the css to do this, we just need the javascript to toggle the correct classes on the correct elements.

**In index.js:**

1. Add an event listener to the divs with the class `.panel`
2. When the panel is clicked, toggle the class `.open` on the panel
3. When the panel is clicked, toggle the class `.open-active` on the first and last `<p>` in each panel.
