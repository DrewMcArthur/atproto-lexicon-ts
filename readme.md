# atproto-lexicon-ts

## WARNING this doesn't work yet, concept WIP

generated typescript code for the atproto lexicon

this repo basically just generates the lexicon code in [the atproto repo](https://github.com/bluesky-social/atproto)
using their [cli generation tool](https://github.com/bluesky-social/atproto/tree/main/packages/lex-cli).

# build yourself
first run `build.sh` to build the atproto submodule (you might need to `git clone` differently to get the atproto repo.  alternatively, adjust `generate.sh` to point to your atproto repo.

second, run `generate.sh`, or take a look for some inspiration.

# usage

this repo already has all the types generated from running generate on the current atproto repo's lexicon.  
you should be able to `yarn add` your way to these types.

1. `yarn add --dev https://github.com/DrewMcArthur/atproto-lexicon-ts.git`
2. `import { OutputSchema as RepoEvent } from "atproto-lexicon-ts/api/src/types/com/atproto/sync/subscribeRepos"` or similar
