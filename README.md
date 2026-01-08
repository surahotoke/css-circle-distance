# CSS Circle Distance
A small CSS-only experiment that connects two circles and displays the distance between them.

No JavaScript is used for the calculation.

## Demo
https://surahotoke.github.io/css-circle-distance

https://github.com/user-attachments/assets/c5171d53-389e-416c-a004-63889954b612

## About
- The circles are moved using `resize`
- The connection line is calculated with CSS trigonometric functions
- The distance is displayed dynamically
- When the circles overlap, the line disappears

This is inspired by modern CSS features such as:
`@property`, `counter()`, `hypot()`, `atan2()`, and conditional styles.

## Notes
- Resize handles have a minimum size of 16×16px, so positions are offset by -8px to align with their center

## Browser Support
Works best in modern Chromium-based browsers.
