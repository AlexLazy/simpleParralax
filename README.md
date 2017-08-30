# simpleParallax

simpleParallax is very simple plugin for add parallax effect on your site.

Check out this **[demo][demo]** to see it in action!

## Setup

Clone this repository or install with npm `npm install --save simpleParallax`.

```javascript
$('#parallax').simpleParallax();
```

## Default options


| Option           | Values              | Default       | Description                                                                                                                                          |
| ------------------- | ------------------- | ------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| `shift`     | `number`   | `5`       | The rate of displacement of the image                                                           |
| `mobile` | `true` or `false`   | `true`       |  Do not initialize on mobile devices              |


### Exemple

```javascript
$('#parallax').simpleParallax({
  shift: 10,
  mobile: false
});
```



## Author

Alexey Cherepanov: [Website][websiterr]

## License

Licensed under [MIT][mit]. Enjoy.

[demo]: http://alexeych.ru/
[websiterr]: http://alexeych.ru/
[mit]: http://www.opensource.org/licenses/mit-license.php
