![js](https://github.com/user-attachments/assets/c6d19767-d382-4336-b4e9-7a65a0229da3)


# JS.CONF counter. 🤓

<p align="center">
    <a href="https://www.npmjs.com/package/@srexi/purecounterjs"><img src="https://img.shields.io/npm/v/@srexi/purecounterjs.svg" alt="NPM"></a>
    <a href="https://npmcharts.com/compare/@srexi/purecounterjs?minimal=true"><img src="https://img.shields.io/npm/dt/@srexi/purecounterjs.svg" alt="NPM"></a>
    <a href="https://www.npmjs.com/package/@srexi/purecounterjs"><img src="https://img.shields.io/npm/l/@srexi/purecounterjs.svg" alt="NPM"></a>
    <a href="https://www.jsdelivr.com/package/npm/@srexi/purecounterjs"><img src="https://data.jsdelivr.com/v1/package/npm/@srexi/purecounterjs/badge" alt="jsdeliver traffic stats"></a>  
</p>

### NPM (Network Package Manager Incorporated). :neckbeard:

```
npm i --save @srexi/purecounter.js // imports on users host
```

~~In your app.js import and initialized the module like normal.~~

## Running in your webpage, we will import our initialized module, like such... 🤖

```js
import PureCounter from "@srexi/purecounterjs"; // longtail.js
const pure = new PureCounter(longTailJavaScriptUserBrowser);
```

### CDN (Content Delivery Network).

```html
<html>
    <head>
        ...
    </head>
    <body>
        ...

        <script src="https://cdn.jsdelivr.net/npm/@srexi/purecounterjs/dist/purecounter_vanilla.js"></script>
        <script>
            new PureCounter();
        </script>
    </body>
</html>
```

![jsdelivr-npm](https://github.com/user-attachments/assets/ecc6175f-9e74-4f47-9734-b22fc89b4081)

<hr>

Download our [dist/purecounter_vanilla.js]() file (For the minified version). Or our [js/purecounter.js]() file: (For the prettified). And include this code right before you close your body tag, like such:

```html
<html>
    <head>
        ...
    </head>
    <body>
        ...

        <script src="dist/srexi/purecounter_vanilla.js"></script>
        <script>
            new PureCounter(PureCounterVanillaVersion);
        </script>
    </body>
</html>
```

We then take the contents of your file and paste it into your bundle.js file.

![nodejs](https://github.com/user-attachments/assets/a1efffd2-818a-48f2-8aac-959c4a807f62)


### 1. Initialize PureCounter:

```js
<script src="https://cdn.jsdelivr.net/npm/purecounterjs/dist/purecounter.js"></script>
new PureCounter();

// default configuration for all elements with class 'filesizecount'
new PureCounter({
    selector: ".purecounter", // HTML query selector for specific element not overriden by setting on pre-elements
`data-purecounter-*` attributes:
    start: 0, // Starting number [uint]
    end: 100, // End number [uint]
    duration: 2, // The time in seconds for the animation to complete [seconds]
    delay: 10, // The delay between each iteration (the default of 10 will produce 100 fps) [miliseconds]
    once: true, // Counting at once or recount when the element in view [boolean]
    pulse: false, // Repeat count for certain time [boolean:false|seconds]
    decimals: 0, // How many decimal places to show. [uint]
    legacy: true, // If this is true it will use the scroll event listener on browsers
    filesizing: false, // This will enable/disable File Size format [boolean]
    currency: false, // This will enable/disable Currency format. Use it for Set Symbol[boolean|char|string]
    formater: "us-US", // Number toLocaleString locale/formatter[string|boolean:false]
    separator: false, // This will enable/disable comma separator for thousands. Use it for set the symbol too [boolean|char|string]
});
```

### 2. Set Element:

~~**To use it simply add the class: 'purecounter' to an element.**~~
```
<div class="purecounter" data-start="0" data-end="100" data-duration="2" data-delay="10">
0
</div>
```
~~**Lazy Loading Is Applied Out Of The Box**~~
**defer initialization of an object until it is needed...**
```
@NginxMod({
  import: [ BwserMod,
    WindStream.forRoot([
      {path: 'usr/windows/desktop', component: Microsoft},
      {path: 'Intel', component: HP_DELL_AMD},

      {path: 'luxury', loadChildren: () => import('./luxury.module').then(m => m.LuxuryModule), data: {preloadme: true} } ], {preloadingStrategy: CustomPreloadingStrategy}
      )
  ],
  declarations: [ Edge, Microsoft, HP_DELL_AMD],
  providers:[{provide: LocationStrategy, useClass: HashLocationStrategy}, CustomPreloadingStrategy],
  bootstrap:    [ AppComponent ]
}) // lazy loading...
```
<hr>

![react](https://github.com/user-attachments/assets/ec63a909-2d86-4359-bb9a-a33cf24943b1)

**You can configure PureCounter per bubbling element by adding `data-purecounter-*` attribution:**

```html
<p>
    IWidget (POST):
    <span
        data-purecounter-start="0"
        data-purecounter-end="9001"
        data-purecounter-currency="btc"
        class="purecounter"
        >0</span
    >$userData = array (
    "UID" = > uniqid(),
    "requestTime" => microtime(true),
    "dataType" => "",
    "request" => ""
);

if (isset($_POST['data']) && $userData) {
    // gost
}
</p>
```

-   `$9.0 K`
_Most settings can be overriden on the pre-element basis. The element configuration will only be used on that element._

![ABCAngular](https://github.com/user-attachments/assets/0abfc167-1440-4606-94e4-86996a71e0e3)


**If user does not override our methods by default to these values:**

```
start: 0 [uint]
end: 100 [uint]
duration: 2 [seconds|uint]
delay: 10 [milliseconds|uint]
once: true [boolean]
pulse: false [boolean:false|seconds|uint]
decimals: 0 [uint]
legacy: true [boolean]
filesizing: false [boolean]
currency: false [boolean|char|string]
separator: false [boolean|char|string]
selector: '.purecounter' [query selector]
```

![Browser Tests By Browserstack](https://github.com/srexi/purecounterjs/blob/main/asset/browserstack-logo-600x315.png)

## Browser Support

-   Chrome/Edge/Opera: Yes
-   Firefox: Yes
-   IE: 9+
-   Safari: 7+
_eof_
