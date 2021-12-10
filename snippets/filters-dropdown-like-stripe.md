---
title: Filters dropdown like Stripe
tags: components, filters
created_at: 2020-10-08T20:48:11+03:00
updated_at: 2020-10-08T20:48:11+03:00
---

## Transform builder

```css
.transform {
    --x-transform-translate-x: 0;
    --x-transform-translate-y: 0;
    --x-transform-rotate: 0;
    --x-transform-skew-x: 0;
    --x-transform-skew-y: 0;
    --x-transform-scale-x: 1;
    --x-transform-scale-y: 1;
    transform: translateX(var(--x-transform-translate-x)) translateY(var(--x-transform-translate-y)) rotate(var(--x-transform-rotate)) skewX(var(--x-transform-skew-x)) skewY(var(--x-transform-skew-y)) scaleX(var(--x-transform-scale-x)) scaleY(var(--x-transform-scale-y));
}
```

## Usage

Use the `transform` utilities to apply a 2D or 3D transformation to an element. This property allows you to rotate, scale, rotate, move or skew elements.

<div class="docs-example bg-surface-secondary rounded p-16">
    <div class="d-flex gap-16">
        <div class="bg-soft-primary p-3 rounded d-flex align-items-center justify-content-center">
            <div class="bg-primary transform translate-x-n1/2 translate-y-n1/2 w-20 h-20 rounded"></div>
        </div>
        <div class="bg-soft-tertiary p-3 rounded d-flex align-items-center justify-content-center">
            <div class="bg-tertiary transform rotate-12 w-20 h-20 rounded"></div>
        </div>
        <div class="bg-soft-warning p-3 rounded d-flex align-items-center justify-content-center">
            <div class="bg-warning transform skew-x-12 w-20 h-20 rounded"></div>
        </div>
        <div class="bg-soft-success p-3 rounded d-flex align-items-center justify-content-center">
            <div class="bg-success transform scale-50 w-20 h-20 rounded"></div>
        </div>
    </div>
</div>

```html
<div class="d-flex">
    <div class="transform translate-x-n1/2 translate-y-n1/2"></div>
    <div class="transform rotate-12"></div>
    <div class="transform skew-x-12"></div>
    <div class="transform scale-50"></div>
</div>

## Remove transform

Use the `.transform-none` to remove this behaviour on any breakpoint.

```html
<div class="transform translate-x-32 transform-md-none">
    ...
</div>
```

## Responsive

Responsive variations also exist for each `transorm` value. Use the `.transform-{breakpoint}` for sm, md, lg, xl, and xxl to any existing transform utility.

```html
<div class="transform-md scale-md-50 scale-lg-100 ..."></div>
```
