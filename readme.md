# Output

Command:

```bash
$ pnpm size
```

```
✔ Adding to empty webpack project
✔ Running JS in headless Chrome

  import { createConfig, http } from 'wagmi'
  Size:         12.96 kB with all dependencies, minified and brotlied
  Loading time: 254 ms   on slow 3G
  Running time: 196 ms   on Snapdragon 410
  Total time:   449 ms

  import { mainnet } from 'wagmi/chains'
  Size:         316 B with all dependencies, minified and brotlied
  Loading time: 10 ms on slow 3G
  Running time: 82 ms on Snapdragon 410
  Total time:   92 ms

  import { injected } from 'wagmi/connectors'
  Size:         6.39 kB with all dependencies, minified and brotlied
  Loading time: 125 ms  on slow 3G
  Running time: 133 ms  on Snapdragon 410
  Total time:   258 ms

  import { walletConnect } from 'wagmi/connectors'
  Size:         85.94 kB with all dependencies, minified and brotlied
  Loading time: 1.7 s    on slow 3G
  Running time: 709 ms   on Snapdragon 410
  Total time:   2.4 s

  import { metaMask } from 'wagmi/connectors'
  Size:         324.61 kB with all dependencies, minified and brotlied
  Loading time: 6.4 s     on slow 3G
  Running time: 1.8 s     on Snapdragon 410
  Total time:   8.2 s
```