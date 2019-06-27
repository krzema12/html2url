Let's say you want to prepare a link that's clickable in most contexts, and it should have such contents:

```
<svg width="100" height="100"><circle cx="50" cy="50" r="40" stroke="green" stroke-width="4" fill="yellow" /></svg>
```

You can convert the contents to an URL-friendly encoding:

```
%3Csvg%20width%3D%22100%22%20height%3D%22100%22%3E%3Ccircle%20cx%3D%2250%22%20cy%3D%2250%22%20r%3D%2240%22%20stroke%3D%22green%22%20stroke-width%3D%224%22%20fill%3D%22yellow%22%20%2F%3E%3C%2Fsvg%3E
```

and use it after a question mark in address of this site:

https://krzema12.github.io/html2url/?%3Csvg%20width%3D%22100%22%20height%3D%22100%22%3E%3Ccircle%20cx%3D%2250%22%20cy%3D%2250%22%20r%3D%2240%22%20stroke%3D%22green%22%20stroke-width%3D%224%22%20fill%3D%22yellow%22%20%2F%3E%3C%2Fsvg%3E
