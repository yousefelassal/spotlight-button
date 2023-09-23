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

- Create a conic gradient with the size of both sides set to 100% of the parent element's width, using `cqw` units – `h-[100cqw]` and `w-[100cqw]`.
- Apply the `spin` animation to the element. You can adjust the duration using square bracket notation: `[animation-duration:3s]`.

    https://github.com/yousefelassal/spotlight-button/assets/76617202/ada98f6b-d505-487a-a967-2d7e136f7e78

- Put a solid background on top of the element.
- Make sure to give some room to pseudo borders, using absolute position properties, e.g. `inset-0.5`


    https://github.com/yousefelassal/spotlight-button/assets/76617202/e69133a3-49f6-4556-8007-cb5ae9f02cae

