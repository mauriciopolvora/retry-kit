# retry-kit

Tiny, dependency-free retry helper for async functions.

```js
import { withRetry } from './src/lib/retry.js'

const data = await withRetry(() => fetch(url).then((r) => r.json()), { attempts: 5, delayMs: 200 })
```

## Development

```bash
npm test
```

Bug reports and PRs welcome. See the issues tab.
