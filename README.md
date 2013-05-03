# Fractional Widths

Generate 1ofx classes for fractional widths

## Installation

```
bower install fonzie-fractional-widths
```

## Usage

```scss
@include fz-FractionalWidths(5);
```

Generates:

```css
.fz-1of5 { width: 20%; }
.fz-2of5 { width: 40%; }
.fz-3of5 { width: 60%; }
.fz-4of5 { width: 80%; }
.fz-5of5 { width: 100%; }
```