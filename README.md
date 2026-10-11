# Prevent Lenis (PeNis)
Lenis is basically the smooth scrolling that some websites have - this removes it

entire program is this line:

`addEventListener('wheel',e=>document.documentElement.classList.contains('lenis')&&e.stopImmediatePropagation(),{capture:true,passive:true})\`

MIT License.
