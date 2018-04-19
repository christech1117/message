# 發信 Message

## 記錄信箱的注意事項

```
因每一家信箱的css規則都不同，所以寫法上有些限制要注意
```

1. 使用 `<table>` 來排版，不要使用 `<div>`，因為 `ios` 內建信箱 `<div>` 會自動 `margin`
2. 網路上的發信系統很多不吃 `<style>` 裡的 `css` ，故需寫在 `<html>` 標籤裡，也不吃外部連結(`bootstrap`)
3. `PC` 上 `gmail` 不吃 `html` 和 `body` 的 `font-family`，故需寫在 `<td>` 的 `style` 裡
4. 可能是 `android` 內建信箱的限制， `小米`、`oppo` 內建信箱不能滿版，故在 `<img>` 及 `<table>` 把 `width` 設 `565px`
5. 手機 `width` 設為 `600px`