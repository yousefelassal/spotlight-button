<div align="center">

# Spotlight Button


https://github.com/yousefelassal/spotlight-button/assets/76617202/5c5328a7-c4a3-4103-a9bc-76ef4db9373a



</div>

## Steps

- Center the contents of the button using flex properties.
- Inside the button, create an absolute element with `container-type: inline-size`. This enables you to use container query units (cqw and cqh).

```html
<button class="group relative mx-auto inline-flex items-center overflow-hidden rounded-full">
    <div class="absolute inset-0 flex items-center [container-type:inline-size]">
      <!-- -->
    </div>
</button>
```
