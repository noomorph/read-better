read-better
===========

**read-better** is just a few CSS rules that make unformatted HTML document easier to read on mobile and desktop devices.

To use it, embed the following two lines:

```html
...
<head>
...
<meta name="viewport" content="width=device-width" /> <!-- required for mobile devices -->
<link rel="stylesheet" type="text/css" href="/path/to/read-better.css"> <!-- your path to css -->
...
</head>
```

Don't forget about ```<doctype>``` in the beginning of document because otherwise IE will jump into quirks mode.

```html
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
```

For quick test on desktop browser you can insert into **head**:

```html
<link rel="stylesheet" type="text/css" href="https://raw.github.com/noomorph/read-better/master/stylesheets/read-better.css">
```

Any suggestions? You are welcome.

Licensed under [Creative Commons License BY 3.0](http://creativecommons.org/licenses/by/3.0/)
