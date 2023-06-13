# Checklists for FE development

Here are checklists that help me not to forget important things.

## Images

- [ ] Add `user-select: none` (CSS) to image containers, `draggable: false` (HTML) to images
- [ ] Set `display: block` on `img` (CSS). Otherwise it might behave randomly 
- [ ] Set `width`, `height`, `alt`  on `img` (HTML)
- [ ] Optimize images. Use tinypng, then convert to webp. Use `loading="lazy"`
- [ ] Display blurry bg to images. Bluhash / extra low resolution img versions / `Image` in NextJS

## Page Load

- [ ] Show spinner until React App starts. Use CSS for spinner

## Hover animations

- [ ] Add `@media (hover: hover) {}` (CSS) for hover animations. Phones don't have hover effects
