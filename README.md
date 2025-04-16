## Overview

This is some example code that can help you to create a following network for a specific user on Bluesky.

## Installation

There are 2 scripts---one in Python and one in R. For Python, you will need to install `atproto`, the wrapper for accessing the Bluesky API.

```
pip install atproto
```
or 
```
mamba install atproto
```

R requires the `tidygraph`, `ggraph`, and `tidyverse` libraries.

## Limitations

This took about 15 minutes for my follower graph, following ~500 people. It doesn't currently do any error handling, and restarts from the beginning if anything goes wrong.
