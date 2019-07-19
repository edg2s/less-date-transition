# LESS date transition
Transition CSS values in LESS based on the current date.

## Requirements

You must use the [Enable Inline Javascript](http://lesscss.org/usage/#less-options-enable-inline-javascript-deprecated-) flag in the LESS compiler: `lessc --js`

## Usage
```less
@import 'path/to/lib/date-transition.less';
```

## Examples

```less
body {
	// Transition from red to blue over 15 years
	.transitionByDate( 2015, 1, 1, 2029, 12, 31, background-color, #f00, #00f );
}
```

```less
.myButton {
	// Increase font-size and padding over 3 months
	.transitionByDate( 2019, 6, 1, 2019, 9, 1, font-size, 12px, 16px );
	.transitionByDate( 2019, 6, 1, 2019, 9, 1, padding, 1px, 6px );
}
```
