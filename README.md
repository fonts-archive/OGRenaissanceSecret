# OG 르네상스 비밀

[배포처 바로가기](https://www.ownglyph.com/trial/design/03b4f007-7db5-4106-b445-c959d0023402)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `OG Renaissance Secret`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/OGRenaissanceSecret/OGRenaissanceSecret.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/OGRenaissanceSecret/OGRenaissanceSecret.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'OG Renaissance Secret';
    font-weight: normal;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/OGRenaissanceSecret/OGRenaissanceSecret.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/OGRenaissanceSecret/OGRenaissanceSecret.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/OGRenaissanceSecret/OGRenaissanceSecret.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/OGRenaissanceSecret/OGRenaissanceSecret.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/OGRenaissanceSecret/subsets/OGRenaissanceSecret-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/OGRenaissanceSecret/subsets/OGRenaissanceSecret-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.


```css
font-family: "OG Renaissance Secret", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
저작재산권은 (주)보이저엑스와 해당 손글씨 제공자에게 있습니다.
해당 폰트를 사용한 인쇄물, 광고물(온라인 포함)의 이미지는
온글잎(또는 (주)보이저엑스) 프로모션을 위해 활용될 수 있습니다.

폰트 파일의 수정 불가
폰트 파일 배포 가능
폰트 파일의 유료 판매 불가
```
