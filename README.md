# Checklists for FE development

Here are checklists that help me not to forget important things.

## Page

- [ ] Add title `<title>Where is the world?</title>`
- [ ] Add description `<meta name="description" content="paste your description here" />`
- [ ] Add favicon `<link rel="icon" type="image/png" href="/favicon.png" />`
- [ ] Add preview image. Via og:, twitter, etc. `<link rel="image_src" href="./assets/preview.webp" />` (there is much more really)

## Images

- [ ] Add `user-select: none` (CSS) to image containers, `draggable: false` (HTML) to images
- [ ] Set `display: block` on `img` (CSS). Otherwise it might behave randomly 
- [ ] Set `width`, `height`, `alt`  on `img` (HTML)
- [ ] Optimize images. Use tinypng, then convert to webp. Use `loading="lazy"`
- [ ] Display blurry versions of images until main images don't load. Bluhash / extra low resolution img versions / `Image` in NextJS / Skeletons
- [ ] (_if an image may be enlarged by clicking_) Set `cursor: zoom-in;` on hover. Consider displaying zoom-in icon on hovering

## Page Load

- [ ] Show spinner until React App starts. Use CSS for spinner

## Hover animations

- [ ] Add `@media (hover: hover) {}` (CSS) for hover animations. Phones don't have hover effects

## Download

- [ ] Display skeletons or spinners when downloading, or in process

