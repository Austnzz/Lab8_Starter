# Lab8-Starter
Names: Austin Choi

## Graceful Degradation
Graceful degradation begins with full CSS, API data, and high res images. THen from there, we go layer by layer while still maintaining the usability. Service Workers on the other hand on offline intercepts all fetches, fulfills them in the cache, and the things like UI, thumbnails, stroed recipes still show. Only live features that require updateing are going to be missing. This way the fallback happens in the browser, the experience is never blocked or slowed sicne all it does is lowers in fidelity rather than crashing due to being offline.

[link](https://austnzz.github.io/Lab8_Starter/)
