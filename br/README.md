## Install

Sentry captures data by using an SDK within your application's runtime.

```bash
pnpm add @sentry/browser
```

## Configure SDK

Initialize Sentry as early as possible in your application's lifecycle.

```javascript

import * as Sentry from "@sentry/browser";

Sentry.init({
  dsn: "https://cf0133940050244ce45ed679485485d0@o4512192354254848.ingest.de.sentry.io/4512192367427664"
});

```

## Verify

This snippet contains an intentional error and can be used as a test to make sure that everything's working as expected.

```javascript
myUndefinedFunction();
```
