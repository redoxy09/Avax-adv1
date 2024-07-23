# Avax-adv1 for Metacrafter AVAX Advanced module 1

## How to create a Subnet using windows🤔

  1. first you must turn on the the wsl(windows subsystem for linux) feature by searching it.
  2. download the ubuntu lts version using microsoft store.
  3. go through this guide now. `https://docs.avax.network/tooling/cli-guides/install-avalanche-cli`
  4. after all the process you are ready with deployment of your own `subnet`
 
## Process to follow : 

1. avalanche subnet create mySubnet
2. Attempted to check if a new version is available, but couldn't find the currently running version information
3. Make sure to follow official instructions, or automatic updates won't be available for you
4. ✔ Subnet-EVM
5. creating subnet mySubnet
6. Enter your subnet's ChainId. It can be any positive integer.
7. ChainId: 12345567
8. Select a symbol for your subnet's native token
9. Token symbol: MYSUBNET
10. ✔ Use latest version
11. ✔ Low disk use    / Low Throughput    1.5 mil gas/s (C-Chain's setting)
12. ✔ Airdrop 1 million tokens to the default address (do not use in production)
13. ✔ No

## After deploying your subnet -

1. Add your displayed network manually in metamask
2. now import a account using private key provided with subnet
3. transfer some token to different account on same network to use your own contracts locally.
4. run your contract as Intended!! 
