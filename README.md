# 조선신명조

[배포처 바로가기](https://event.chosun.com/100/100font.html)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `ChosunSm`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/ChosunSm/ChosunSm.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/ChosunSm/ChosunSm.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'ChosunSm';
    font-weight: normal;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/ChosunSm/ChosunSm.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/ChosunSm/ChosunSm.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/ChosunSm/ChosunSm.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/ChosunSm/subsets/ChosunSm-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/ChosunSm/subsets/ChosunSm-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.


```css
font-family: "ChosunSm", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
'조선100년체'의 지적재산권은 방일영문화재단에 있으며, 조선일보 전용서체 9종의 지적재산권은 (주)조선일보사에 있습니다. 
'조선100년체'와 조선일보 전용서체 9종은 개인 및 기업 사용자에게 무료로 제공됩니다. 
사용자들은 이를 다른 이에게 자유롭게 배포할 수 있습니다. 
다만 어떠한 경우에도 복사 또는 배포에 따른 대가를 요구하거나 수정해서 판매할 수 없으며, 배포된 형태 그대로 사용해야 합니다.
```
