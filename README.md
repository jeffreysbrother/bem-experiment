An existing project utilizing Sass and Bootstrap was updated to (partially) reflect the BEM methodology. This is currently incomplete; there are no "modifiers" and I am unsure of how (or whether) Bootstrap should be used in this context.

###important features of BEM

* no IDs used for styling
* no element selectors
* no descendant selectors
* class naming convention: `.block__element--modifier`

##benefits

* the elimination of IDs and descendant selectors rids the project of unnecessary specificity; overrides are therefore more predictable.
* modularity is increased when we force our styles to have low specificity
