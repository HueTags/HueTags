# HueTags
> HTML Preprocessor written in JavaScript that permits to write color tags as ```<r></r>```, that are faster than ```<span style="color: red;"></span>```

## How do I use it ? 
To use the HueTags prepocessor, include it trough the CDN link, using the ```<script></script>``` tag in the html file that uses it. \
CDN link : [https://cdn.jsdelivr.net/gh/HueTags/HueTags@main/main.js](https://cdn.jsdelivr.net/gh/HueTags/HueTags@main/main.js)

## Features & Specification
Currently, the Preprocessor has very few features. Many will be added later. \
The current features are: \
```<r></r>``` or ```<red></red>``` to color the text red \
```<g></g>``` or ```<green></green>``` to color the text green \
```<blue></blue>``` (```<b></b>``` already exists) to color the text blue \
```<color-def name="dodgerblue" color="#1e90ff" />``` to define a color tag.
> The attribute color contain a color written as you write it in CSS (e.g. ```rgb(30, 144, 255)```, ```hsl(210, 100%, 56%)```...)
