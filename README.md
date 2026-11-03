# AI Home Styler — Интерактивный баннер-калькулятор

Интерактивный промо-баннер для примерки дизайна интерьера с бегунком «До/После», анимированной AI-плашкой и яркой оранжевой кнопкой действия (CTA).

## 🔗 Демо-ссылки (GitHub Pages)

- 📱 **Демо с мокапом смартфона:**  
  [https://watizzzlove.github.io/calculator-banner/](https://watizzzlove.github.io/calculator-banner/)

- 🧩 **Чистый виджет (контентная часть БЕЗ мокапа):**  
  [https://watizzzlove.github.io/calculator-banner/widget.html](https://watizzzlove.github.io/calculator-banner/widget.html)

---

## 💻 Варианты интеграции для клиента

### Вариант 1. Вставка через iframe (самый простой)
Вставьте данный код в любое место на сайте (Tilda, Webflow, WordPress, самописный сайт):

```html
<iframe 
  src="https://watizzzlove.github.io/calculator-banner/widget.html" 
  width="100%" 
  height="450" 
  style="border: none; max-width: 390px; width: 100%; display: block; margin: 0 auto; border-radius: 20px; overflow: hidden;"
  loading="lazy">
</iframe>
```

---

### Вариант 2. Прямой HTML-код виджета
Код виджета без лишних рамок находится в файле [`widget.html`](widget.html).

Картинки для самостоятельного хостинга:
- [`before.jpg`](before.jpg) — изображение «До»
- [`after.jpg`](after.jpg) — изображение «После»

Либо можно использовать абсолютные ссылки с CDN GitHub Pages:
- `https://watizzzlove.github.io/calculator-banner/before.jpg`
- `https://watizzzlove.github.io/calculator-banner/after.jpg`
