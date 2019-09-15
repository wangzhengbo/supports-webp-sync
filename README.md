# supports-webp-sync

Checks if the browser supports WebP without any costly requests.

May give false negatives for some obscure non-WebKit browsers.

## Usage

```js
import { checkWebPSupport } from 'supports-webp-sync'

if (checkWebPSupport()) {
  // Get some WebP images
}
```
