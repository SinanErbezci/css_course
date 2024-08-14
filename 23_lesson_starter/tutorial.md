-- Command + Shift + P -> Command Pallete
-- >Sort Lines Ascending -> sorts lines by alphabetically
-- BEM. Block Element Modifier. Naming convention.

-- Block Elements
starting styles.
.btn {
    width:....
}
...
...
...
-- Modifiers (Which are incremental changes to the block elements)
two dash after block name
.btn--secondary {
    background-color: yellow;
}
-- Elements (No standalone meaning. Semantically tied to the block)
header__btn {
    btn style of header's child.
}