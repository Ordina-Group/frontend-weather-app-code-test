# Weather Widget

Create a weather widget for use in the webbrowser that provides us with a weather forecast.

We've included an 'icons' folder for your use.

We recommend using [Tomorrow.io Weather API](https://www.tomorrow.io/weather-api/) or [OpenWeatherMap](https://openweathermap.org/api/one-call-4) for fetching the data.
Note: Due to the browser's Same-Origin Policy, direct client-side requests to these APIs will be blocked and will expose your API keys. To keep keys secure, route requests through a same-origin proxy:
* **Development Proxy:** Configure a proxy in your dev server (e.g., Vite's `server.proxy`) to forward requests to the API during local development.
* **Backend Server / Proxy:** If using a dedicated backend (e.g., Express) or a full-stack framework (e.g., Next.js, Nuxt), fetch the data server-side where Same-Origin Policy restrictions do not apply.

**Things to consider:**

* We recommend that you use a framework (ie: Angular, React, VueJS)
* You should be able to explain the reasoning behind your choices

## Assessment

For the assessment of this test we will review all aspects of the work delivered.
The assignment is intentionally left vague such as to enable you to show yourself from your best side.
You can score points with anything/everything, so long as it is done well.

Below follows a list of things that can score you points. This list is of course not exhaustive.
You are *not* expected to include all or even most of the points below in your assignment.
Choose a number of things from the list and invest your time wisely.

* Code quality
  * Coding standards
  * Extensibility
  * Structure
  * Abstraction
  * Readability
  * Comments
  * Function / Variable / Class names
  * Error handling
* Automated tests
  * Unit tests
  * End to end tests
  * Good test-coverage
* Documentation
* Visually attractive results
* Usability
  * How much information do you provide?
  * How easy is it to read what's important?
* Accessibility
  * Visual impairment
  * Screen readers
  * Navigation
* Production-readiness
  * Browser support
  * Load speed (First meaningful paint, first contentful paint, interaction ready)
* Technology-used (Examples:)
  * Code splitting
  * Lazy loading
  * ES6
  * Typescript
  * D3
  * PWA
* SEO