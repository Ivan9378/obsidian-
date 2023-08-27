created:2023-01-19 19:56

[[bibliography]]

### Reference:
1. [什麼是 CMYK？製圖前做好這件事降低色偏與重印的機率 – 工程師布萊克](https://aidaidme.com/cmyk-color-model-intro/) [[Obsidian-Highlights]]

<h2>RGB 顏色是什麼？</h2>
- <mark style="background: #FF5582A6;">紅色</mark>
- <mark style="background: #BBFABBA6;">綠色</mark>
- <mark style="background: #ADCCFFA6;">藍色</mark>
>RGB 是光的三原色
>3 種顏色的燈光打在一起時，可以產生白色光
>顏色的範圍定在 0~255 之間，當數值都是 0 ，表示黑色；反之，當數值都是 255，表示白色
>總共有 256 * 256 * 256 種顏色，約有 1677 萬種顏色
>最常用在電腦螢幕、舞台燈光或是相機上
<h2>CMYK 顏色是什麼？</h2>
- <mark style="background: #ABF7F7A6;">青色</mark>
- 洋紅色
- <mark style="background: #FFF3A3A6;">黃色</mark>
- 黑色
> 運用於印刷行業的一種色彩模式
> 青色 (Cyan)、洋紅色 (Magenta)、黃色 (Yellow) 組成的印刷三原色。
> 3 個原色了，黑色就可以調配出來了，怎麼還需要黑色呢？理由很簡單，就是省錢
> 3 種顏色的範圍定在 0~100 之間，當數值都是 100，表示黑色；反之，當數值都是 0，表示白色
>總共有 101 * 101 * 101 種顏色，約有 103 萬種顏色

### 色彩模型 (Color Model)
- **提供一種定義顏色的方法，每種顏色都是經由特定的顏色組成的**。
- 參考這種顏色模型發展出來的顏色組合，稱為<mark style="background: #FFB86CA6;">色彩空間 (Color Space)</mark>或色域
- 在 RGB 色彩模型中，有幾個比較常見的色彩空間：
    - Adobe RGB
    - sRGB
    - ProPhoto RGB
- 在 CMYK 色彩模型中，有幾個比較常見的色彩空間：
    - Japan Color 2001 Coated
    - U.S. Sheetfed Coated
    - U.S. Web Coated (SWOP)

## 結論：
- CMYK 的顏色數量少很多
- 小範圍色彩空間的顏色能夠轉換到大範圍的色彩空間 (可能略有一點差異)，但反過來說就不成立
- Adobe RGB 比 sRGB 支援更多綠色，使顏色更鮮豔

<h2>印刷時如何避免顏色跑掉？</h2>
 - 兩者的顏色數量實在差距很大，顏色都會有差距
 - 影響色差的因素還有紙張材質、印表機、墨水好壞及顯示器未校色...等的因素
 - **建議去比較專業的印刷輸出店印製你的作品！**
 - **從 RGB 轉成 CMYK 顏色一定有差異**
 - 若新的設計案開始時就已經定在 CMYK 色彩模式了，此時就可以大幅縮小色差的機率。