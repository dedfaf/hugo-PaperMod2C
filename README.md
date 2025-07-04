# PaperMod2C

This repository is created to apply the changes from [pull request #675](https://github.com/adityatelange/hugo-PaperMod/pull/675)(Toc on the side) to the [Hugo PaperMod theme](https://github.com/adityatelange/hugo-PaperMod). It may occasionally be synchronized with the upstream repository in the future.

## Additional functions

Add or modified some functions, as below:

### Hero Image

I’ve added a feature for a large image on the homepage (For personal use). Add 

``` yaml
# hugo.yaml
params:
  ...

  homeInfoParams:
    Title: ...
    Content: ...
    Image: "Your Image URL Here"

```

in `hugo.yaml` (or other formats) to enable it.

### footbar text above

Allows to put footbar text on a new line above.

``` yaml
# hugo.yaml
params:
  ...

  footer:
    text: ...
    textAbove: true
```

And also, the top menu is aligned to the left (which I personally prefer).

## Install & Details

check <https://adityatelange.github.io/hugo-PaperMod/>, you only need to change the submodule URL to this repo.
