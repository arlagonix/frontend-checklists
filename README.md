# Checklists for FE development

I write these checklists for myself only.

## Global advices

- [ ] Use Git
- [ ] Peer review code
- [ ] Add CI/CD
- [ ] Use transparent task management process
- [ ] 1 task = 1 branch in Git
- [ ] Add autotests
- [ ] Use an error monitoring system

Sources:
* [(Russian) Плохие практики разработки, которые до сих пор встречаю в стартапах](https://habr.com/ru/post/719352/)
* [(Russian) Miro scheme](https://miro.com/app/board/uXjVP7vl1vk=/)

## Working with images

- [ ] Add `user-select: none` (CSS) to image containers, `draggable: false` (HTML) to images
- [ ] Add `@media (hover: hover) {}` (CSS) for hover animations. Helps to avoid problems with strange effects on phones
