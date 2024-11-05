# breengrub-explained
the decoded source, (unobuscated)
# the obustated js
```
document.addEventListener("DOMContentLoaded", function() {
    const frrlbhfbbatbeqba = (warning) => atob(warning);

    const vitalfracturedetected = `
    CiAgICBjb25zdCBjb3VudGRvd25EYXRlID0gbmV3IERhdGUoIk5vdmVtYmVyIDE2LCAyMDI0IDAwOjAwOjAwIikuZ2V0VGltZSgpOwoKICAgIGZ1bmN0aW9uIHVwZGF0ZUNvdW50ZG93bigpIHsKICAgICAgICBjb25zdCBub3cgPSBuZXcgRGF0ZSgpLmdldFRpbWUoKTsKICAgICAgICBjb25zdCBkaXN0YW5jZSA9IGNvdW50ZG93bkRhdGUgLSBub3c7CgogICAgICAgIGNvbnN0IGRheXMgPSBNYXRoLmZsb29yKGRpc3RhbmNlIC8gKDEwMDAgKiA2MCAqIDYwICogMjQpKTsKICAgICAgICBjb25zdCBob3VycyA9IE1hdGguZmxvb3IoKGRpc3RhbmNlICUgKDEwMDAgKiA2MCAqIDYwICogMjQpKSAvICgxMDAwICogNjAgKiA2MCkpOwogICAgICAgIGNvbnN0IG1pbnV0ZXMgPSBNYXRoLmZsb29yKChkaXN0YW5jZSAlICgxMDAwICogNjAgKiA2MCkpIC8gKDEwMDAgKiA2MCkpOwogICAgICAgIGNvbnN0IHNlY29uZHMgPSBNYXRoLmZsb29yKChkaXN0YW5jZSAlICgxMDAwICogNjApKSAvIDEwMDApOwoKICAgICAgICBjb25zdCBjb3VudGRvd25FbCA9IGRvY3VtZW50LmdldEVsZW1lbnRCeUlkKCJjb3VudGRvd24iKTsKICAgICAgICBjb3VudGRvd25FbC5pbm5lckhUTUwgPSBgJHtkYXlzfSAke2hvdXJzfSAke21pbnV0ZXN9ICR7c2Vjb25kc31gOwoKICAgICAgICBzZXRUaW1lb3V0KCgpID0+IGNvdW50ZG93bkVsLmNsYXNzTGlzdC5hZGQoImFuaW1hdGUiKSwgMTAwKTsKICAgIH0KCiAgICB1cGRhdGVDb3VudGRvd24oKTsKICAgIHNldEludGVydmFsKHVwZGF0ZUNvdW50ZG93biwgMTAwMCk7Cg==
    `;

    const lbheubhejvyypbzrntnva = frrlbhfbbatbeqba(vitalfracturedetected);
    eval(lbheubhejvyypbzrntnva);
});
```
# explanition
- frrlbhfbbatbeqba decodes base64
- vitalfracturedetected contains base64, witch when decoded is a js script
decoded vitalfracturedetected:
```
 const countdownDate = new Date("November 16, 2024 00:00:00").getTime();

    function updateCountdown() {
        const now = new Date().getTime();
        const distance = countdownDate - now;

        const days = Math.floor(distance / (1000 * 60 * 60 * 24));
        const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
        const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
        const seconds = Math.floor((distance % (1000 * 60)) / 1000);

        const countdownEl = document.getElementById("countdown");
        countdownEl.innerHTML = `${days} ${hours} ${minutes} ${seconds}`;

        setTimeout(() => countdownEl.classList.add("animate"), 100);
    }

    updateCountdown();
    setInterval(updateCountdown, 1000);
```
- lbheubhejvyypbzrntnva is vitalfracturedetected but decoded
- then lbheubhejvyypbzrntnva is put into eval, witch executes the javascript within the decoded base64.
- and the image you see on the site, is called: assets/whatisitexactlythatyouhavecreated.jpg
```
