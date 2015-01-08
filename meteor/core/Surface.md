Surface
=======

```js
  var foo = new library.meteor.core.Surface({
    template: Template.hello,
    size: [undefined, undefined],
    properties: {
       backgroundColor: "hsl(" + (3 * 360 / 10) + ", 100%, 50%)",
       lineHeight: "400px",
       textAlign: 'center',
    }
  });
```

You can add data too...
```js
  var foo = new library.meteor.core.Surface({
      template: options.template,
      data: data.get(),
      size: [undefined, undefined],
      properties: {
         backgroundColor: "hsl(" + (3 * 360 / 10) + ", 100%, 50%)",
         lineHeight: "400px",
         textAlign: 'center',
      }
  });
```