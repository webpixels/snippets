---
title: Filters dropdown like Stripe
tags: components, filters
created_at: 2020-10-08T20:48:11+03:00
updated_at: 2020-10-08T20:48:11+03:00
---

### Material

Material is a comprehensive design system developed by Google and released in 2014. This design system includes a color palette picker, design best practices, typography rules and guidelines, and more. You can use it to develop both mobile apps and various web projects. Material has 10.6k stars on GitHub.

[Learn more](https://material.io/design)


### Fluent

The Fluent design system is an open design language developed by Microsoft. This design system is a great choice if you want the end project to have a clean and simple, yet cohesive design. The system itself revolves around five basic principles: light, depth, motion, material, and scale. It was designed to be used across all platforms and devices. FluentUI alone has 8.8k stars on GitHub.

[Learn more](https://www.microsoft.com/design/fluent/#/)


### Shopify Polaris

The main purpose behind Shopify Polaris design system was to provide a unified and beautiful design guidelines for store designs. This design system lays out the rules for designing every part of a Shopify store’s interface, including content, components, design, and pattern guidelines. Polaris has 3.4k stars on GitHub.

[Learn more](https://polaris.shopify.com/)

```html
<div class="horizontal-snap">
  <a href="#"><img src="https://picsum.photos/id/1067/640/640"></a>
  <a href="#"><img src="https://picsum.photos/id/122/640/640"></a>
  <a href="#"><img src="https://picsum.photos/id/188/640/640"></a>
  <a href="#"><img src="https://picsum.photos/id/249/640/640"></a>
  <a href="#"><img src="https://picsum.photos/id/257/640/640"></a>
  <a href="#"><img src="https://picsum.photos/id/259/640/640"></a>
  <a href="#"><img src="https://picsum.photos/id/283/640/640"></a>
  <a href="#"><img src="https://picsum.photos/id/288/640/640"></a>
  <a href="#"><img src="https://picsum.photos/id/299/640/640"></a>
</div>
```
Another useful example is defining shared customized styles for certain variants of an element. This allows the customization of whole trees of components without having to repeat any styles. The following example demonstrates cascading even better than the previous one. It also introduces the idea of sharing styles between different elements:

```css
.btn {
  --bg-color: #002299;
  --text-color: #fff;
  --highlight-color: #669900;

  background-color: var(--bg-color);
  color: var(--text-color);
}
/* --highlight-color is also available to the children of .btn */
.btn .highlight {
  color: var(--highlight-color);
}
/* .btn.danger .highlight will use the --highlight-color defined in .btn-danger */
.btn-danger {
  --bg-color: #dd4a68;
  --text-color: #000;
  --highlight-color: #990055;
}
```
