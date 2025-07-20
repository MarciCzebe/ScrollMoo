# ScrollMoo

ScrollMoo is a pure JavaScript-based tool that lets you create high-performance, keyframed scroll animations. Whether you're a professional web developer or just familiar with HTML, CSS, and JavaScript basics, the simplicity of ScrollMoo will make it easy and enjoyable to create spectacular web animations.

For more information, please visit [ScrollMoo.com](https://scrollmoo.com)
## Demos

Check out multiple demos on [ScrollMoo's website](https://scrollmoo.com/demos).

## Docs

You can find [full documentation here](https://scrollmoo.com/docs/).


## Installation
You can find detailed [installation guide here](https://scrollmoo.com/installation).

### CDN
If you prefer to use a CDN

```javascript
<script src="https://cdn.jsdelivr.net/npm/scrollmoo@1.1.0/dist/scrollmoo.min.js"></script>
```

### NPM
You can also install it with NPM

```javascript
npm install scrollmoo
```
    
## Usage

```javascript
import ScrollMoo from "scrollmoo"; // NPM

let SM = ScrollMoo({
    ".your-element": {
        markers: true, // only during the development
        keyframes: {
            transform: {
                rotate: {
                    100: "360deg"
                }
            }
        }
    }
});
```


## License

[MIT](https://choosealicense.com/licenses/mit/)

Copyright (c) 2025, ScrollMoo.
