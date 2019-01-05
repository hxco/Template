![HTML Single Page HXCO General Template - Screenshot](https://upload.cc/i1/2018/10/22/yX50bQ.png "HXCO General Template")


# Template
> HXCO General Template Is A HTML Single Page That Used By [@HXCO](https://github.com/hxco) Widely Where Web Services Are Published.

Demo Site: [https://template.hxco.org](https://template.hxco.org)

# Installation

## General Way

```
git clone https://github.com/hxco/Template.git
```

## Quickest Way

Get your site environment ready (i.e. nginx config), then -
```
wget https://hxis.me/template -O index.html
```

## Why HXCO Template?
 - **Easy to use** - You will only need to download the whole repo [here](https://github.com/hxco/Template/archive/master.zip) or clone it to your server by using `git clone https://github.com/hxco/template` then modify the words inside sightly, then it will be ready to release!

- **Muitiple Usage** - When you need to create a notification page, especially when in a rush, or you need to park a domain / subdomain for future usage.

- **Excellent performance** - We keep nearly everything on CDN (Content Delivery Network), this includes [jsDelivr](https://jsdelivr.com) and [Google Fonts Build-in CDN](https://font.google.com). For our own `Style.CSS` file, we simply put it on [GitHub Pages](https://pages.github.com), but it still have a overall good speed. So generally, HXCO Gerneral Template can have excellent performance around the globe.

- **Continuous maintenance** - According to our fantastic cooperation mode inside HXCO, this project as our website interface, will get maintained frequently. We would strongly recommend you keep how we import the `Style.CSS`, which looks like this:

```    
    <!-- Preload Style.css -->
    <link href="https://template.hxco.org/style.min.css" rel="preload" as="style">
    <link href="https://template.hxco.org/style.min.css" rel="stylesheet">
```

This will make your template always the same as our template. We will continue to improve the user interface and apply it to your website once it has changed. We will definitely increase the CDN option of `Style.CSS` to provide a better experience when loading, especially for users in China.

## Credit
Great thanks to [@metowolf](https://github.com/metowolf). This project is under the inspiration of his [METO API +](https://api.i-meto.com) (now it's https://api.i-meto.com.cache.hxco.org).

And I would also thanks [@Dreamer-Paul](https://github.com/dreamer-paul), and every one in [@HXCO](https://hxco.org).


> This project is released under the [MIT License](https://github.com/hxco/Template/blob/master/LICENSE). [Tech HXCO 2018](https://github.com/hxco) All Rights Reserved.
