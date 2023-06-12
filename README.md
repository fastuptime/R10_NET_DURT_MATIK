# R10_NET_DURT_MATIK

```js
function getXpath(path) {
  return document.evaluate(path, document, null, XPathResult.FIRST_ORDERED_NODE_TYPE, null).singleNodeValue;
}

function durt() {
  getXpath("/html/body/main/div[1]/div[3]/div/a[1]").click();
  getXpath("/html/body/main/div[1]/div[3]/div/ul/li[1]/a").click();
  console.log("Dürtüldü");
}

durt();

setInterval(durt, 1 * 60 * 1000); // 1 dakika
```

Console ekranına yapıştırın profile girdikten sonra


---
- ✨ [Destek İçin](https://fastuptime.com) <br>
- 💕 [Discord](https://fastuptime.com/discord)<br>
- 🎖️ [FasterHost Technology](https://fasterhost.tech/)<br>
- ✨ İletişim için [Tıkla!](mailto:fastuptime@gmail.com)<br>

# License
- Its protected by Creative Commons ([CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/))

<a href="https://creativecommons.org/licenses/by-nc-sa/4.0/" title="BYNCSA40"><img src="https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png"></a>
