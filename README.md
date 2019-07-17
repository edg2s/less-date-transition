# LESS date transition
Transition CSS values in LESS based on the current date.

## Example

```less
.myClass {
	// Transition from red to blue over 15 years
	.transitionByDate( 2015, 1, 1, 2029, 12, 31, background-color, #f00, #00f );
}
```
