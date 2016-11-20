[Docs and Demos](https://sparhami.github.io/time-selector)

`<time-selector>` lets you manage a selection based on time. 

Example:

    <time-selector selected="{{selected}}">
      <time-range start="11.5" end="14" name="lunch"></time-range>
      <time-range start="18" end="22" name="dinner"></time-range>
    </time-selector>

    <paper-tabs attr-for-selected="name" selected="{{selected}}">
      <paper-tab name="lunch">Lunch</paper-tab>
      <paper-tab name="dinner">Dinner</paper-tab>
    </paper-tabs>

Updating either the reference time or timezone offset will trigger the selected
value to be updated.

The `start` and `end` attributes of a `<time-range>` are specified in a 24 hour
format.

This is not an official Google product.
