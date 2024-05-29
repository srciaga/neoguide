A short beginner's guide to making a website on [Neocities](https://neocities.org/). 

**[Go read the guide here!](https://srciaga.github.io/neoguide/)**

The guide is written in Markdown and the HTML is generated with Pandoc.

Using [chota](https://github.com/jenil/chota), a micro (3kb) CSS framework.

To generate `index.html`:

```sh
pandoc --standalone --template=template.html guide.md -o index.html
```
