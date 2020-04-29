# bulma-grouped
Bulma's extension to create grouped cards and boxes

[![npm](https://img.shields.io/npm/v/bulma-grouped)](https://www.npmjs.com/package/bulma-grouped)

## Quick install
### NPM
[NPM package](https://www.npmjs.com/package/bulma-grouped)
```sh
npm install bulma-grouped
```
### Import
You can import the CSS or SASS file into your project using this snippet after importing 'bulma':
```sh
import 'bulma-grouped/dist/css/bulma-grouped.min.css'
```
or
```sh
import 'bulma-grouped/dist/css/bulma-grouped.sass'
```

Usage
---
```html
<div class="container">
    <div class="box is-grouped">
        <article class="media">
            <div class="media-left">
                <figure class="image is-64x64">
                    <img src="https://bulma.io/images/placeholders/128x128.png" alt="Image">
                </figure>
            </div>
            <div class="media-content">
                <div class="content">
                    <p>
                        <strong>John Smith</strong> <small>@johnsmith</small> <small>31m</small>
                        <br>
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean efficitur sit amet massa
                        fringilla egestas. Nullam condimentum luctus turpis.
                    </p>
                </div>
            </div>
        </article>
    </div>
    <div class="box is-grouped">
        <article class="media">
            <div class="media-left">
                <figure class="image is-64x64">
                    <img src="https://bulma.io/images/placeholders/128x128.png" alt="Image">
                </figure>
            </div>
            <div class="media-content">
                <div class="content">
                    <p>
                        <strong>John Smith</strong> <small>@johnsmith</small> <small>31m</small>
                        <br>
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean efficitur sit amet massa
                        fringilla egestas. Nullam condimentum luctus turpis.
                    </p>
                </div>
            </div>
        </article>
    </div>
    <div class="box is-grouped">
        <article class="media">
            <div class="media-left">
                <figure class="image is-64x64">
                    <img src="https://bulma.io/images/placeholders/128x128.png" alt="Image">
                </figure>
            </div>
            <div class="media-content">
                <div class="content">
                    <p>
                        <strong>John Smith</strong> <small>@johnsmith</small> <small>31m</small>
                        <br>
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean efficitur sit amet massa
                        fringilla egestas. Nullam condimentum luctus turpis.
                    </p>
                </div>
            </div>
        </article>
    </div>
</div>
```

Example
---
![Example usage](https://alakise.com/github/bulma-grouped.png)

Integration to Bulma
---
- Clone the [bulma repo](https://github.com/jgthms/bulma)
- Under the `sass` folder, create a new folder called `extensions`
- In this new folder, create a new file `bulma-grouped.sass`
- Copy the code form the `bulma-grouped repo`'s [dist/css/bulma-grouped.sas](https://github.com/alakise/bulma-grouped/blob/master/dist/css/bulma-grouped.sass) file into your new file
- In the same folder create a new file `_all.sass` (this is not required, but will help when you add more extensions)
- In this file add this code:
```
@charset "utf-8"

@import "bulma-grouped.sass"
```
At the end of the `bulma.sass` file, add this line: `@import "sass/extensions/_all"`
Now, you can just build the bulma project with `npm run build`, and the output will be available in the `css folder`.

OR

- Just add the 'bulma-grouped.sass' or 'bulma-grouped.min.css' in any way you want it.

