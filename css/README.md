# WebDoc CSS

This is CSS standard chapter entry, you can start read from here.

- [Property order](#Property-order)

<a name="Property-order"></a>

### # Property order

**The properties of CSS should be ordered consistently and grouped by block.**

Use consistent order and same grouped rule, you’ll know clearly where to add properties and how properties are defined.

We group properties according to element characteristics as follow block: positioning, box model, typographic, visual, misc.

You should set property order like this:

1. Positioning
2. Box model
3. Typographic
4. Visual
5. Misc

Position is put first, it decide how an element is positioned in a document, be independent or related.

Box model is in second place, it define an element size and layout.

The remaining ungrouped properties are placed last.

Bad

```
.app-container {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 100;
  display: block;
  float: right;
  width: 100px;
  height: 100px;
  font: normal 13px "Helvetica Neue", sans-serif;
  line-height: 1.5;
  color: #333;
  text-align: center;
  background-color: #f5f5f5;
  border: 1px solid #e5e5e5;
  border-radius: 3px;
  opacity: 1;
}
```

Good

```
.app-container {
  /* Positioning */
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 100;

  /* Box model */
  display: block;
  float: right;
  width: 100px;
  height: 100px;

  /* Typographic */
  font: normal 13px "Helvetica Neue", sans-serif;
  line-height: 1.5;
  color: #333;
  text-align: center;

  /* Visual */
  background-color: #f5f5f5;
  border: 1px solid #e5e5e5;
  border-radius: 3px;

  /* Misc */
  opacity: 1;
}
```
