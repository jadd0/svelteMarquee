## Svelte Marquee

This package allows you to create a simple marquee in Svelte

## How to use:

Download the package using:

```terminal
npm i sveltemarquee
```

Then import it into your project with:

```javascript
import { SvelteSimpleMarquee } from 'sveltsimpleemarquee';
```

Then use it with:

```svelte
<SvelteMarquee>
  <h1>Hello World!</h1>
</SvelteMarquee>
```

The speed is automatically set to 50 seconds, but it can be changed by passing a value into the prop:

```svelte
<SvelteMarquee speed={20}>
  <h1>Hello World!</h1>
</SvelteMarquee>
```

Thank you for using my package! :)