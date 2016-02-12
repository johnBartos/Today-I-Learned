##Responsive viewport
To make a website fit to the width of the screen (rather than defaulting to a zoomed-out view), use the `viewport` meta tag

`<meta name="viewport" content="width=device-width, initial-scale=1, initial-scale=1" />`

`width=device-width` will use the true width of the screen

`initial-scale=`' sets a 1-to-1 mapping between CSS pixels and display independent pixels (an abstraction of a pixel using real measurements) when the page loads. it controls the zoom - 1 means don't
