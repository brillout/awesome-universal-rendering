#### Static Pre-Rendering

*Some static pre-renderers, instead of generating HTML upon a generated DOM, directly render your pages to HTML.*

 - [Prerender SPA Plugin](https://github.com/chrisvfritz/prerender-spa-plugin#readme) - Uses Puppeteer to crawl & render your pages.
 - [react-snap](https://github.com/stereobooster/react-snap#readme) - Uses Puppeteer to crawl & render your pages.
 - [prep](https://github.com/prismagraphql/prep#readme) - Uses Chromeless to crawl & render your pages.
 - [SSG webpack plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin#readme) - Directly render your pages to HTML. You provide render functions and routes. All routes are rendered at build-time using the render functions you provided. Also has a crawl mode to use a headless browser to automatically discover your website's URLs.
