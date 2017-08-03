# \<dom-flip\>
🔀 FLIP move for Polymer v2!

## Installation
This element lives on bower. Install with `bower install --save dom-flip`.

## Usage
```html
<link rel="import" href="bower_components/dom-flip/dom-flip.html">
 
<dom-flip>
    <template is="dom-repeat" items="[[items]]">
        <my-item data-flip-id$="[[item.id]]">[[item.name]]</my-item>
    </template>
</dom-flip>
```

Although we wish it did, this element does not work with `<iron-list>` at the moment.