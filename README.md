An existing project utilizing Sass and Bootstrap was updated to (partially) reflect the BEM methodology. This is currently incomplete; there are no "modifiers" and I am unsure of how (or whether) Bootstrap should be used in this context.

###important features of BEM

* no IDs used for styling
* no element selectors and no descendant selectors (except for where I am extending Bootstrap classes)
* class naming convention: `.block__element--modifier`

###benefits

* the elimination of IDs and descendant selectors rids the project of unnecessary specificity; overrides are therefore more predictable.
* modularity is increased when we force our styles to have low specificity



See [this link](https://coderwall.com/p/wixovg/bootstrap-without-all-the-debt) for information on what I refer to as "extending Bootstrap classes". I'm not sure if this is a good idea because it forces you to use element selectors and descendant selectors.

It's also not clear whether unique semantic tags (like `<header>` and `<footer>`) should have class names just for the sake of adhering to the BEM philosophy.
