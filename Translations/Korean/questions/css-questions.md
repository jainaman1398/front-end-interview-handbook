# CSS 질문

* [CSS 선택자 특이성은 무엇이며 어떻게 작동합니까?](#css-선택자-특이성은-무엇이며-어떻게-작동합니까)
* ["Resetting"과 "Normalizing" CSS 의 차이점은 무엇입니까? 당신은 무엇을 선택할 것이며, 그 이유는 무엇입니까?](#resetting과-normalizing-css의-차이점은-무엇입니까-당신은-무엇을-선택할-것이며-그-이유는-무엇입니까)
* [`float`이 어떻게 작동하는지 설명하세요.](#float이-어떻게-작동하는지-설명하세요)
* [`z-index`와 쌓임 맥락(stacking context)이 어떻게 형성되는지 설명하세요.](#z-index와-쌓임-맥락stacking-context이-어떻게-형성되는지-설명하세요)
* [블록 서식 문맥(BFC)과 작동 방식을 설명하세요.](#블록-서식-문맥bfc과-작동-방식을-설명하세요)
* [clear 하는 방법에는 어떤 것이 있으며, 각각 어떤상황에 적합합니까?](#clear하는-방법에는-어떤-것이-있으며-각각-어떤상황에-적합합니까)
* [CSS 스프라이트는 무엇입니까? 그리고 당신이 페이지 나 사이트에 구현하는 방법도 설명해주세요.](#CSS-스프라이트는-무엇입니까-그리고-당신이-페이지나-사이트에-구현하는-방법도-설명해주세요)
* [브라우저 별 스타일링 문제를 해결하는 방법에 대해 어떻게 생각하십니까?](#브라우저-별-스타일링-문제를-해결하는-방법에-대해-어떻게-생각하십니까)
* [기능이 제한된 브라우저의 페이지는 어떻게 처리합니까? 어떤 기술/프로세스를 사용하십니까?](#기능이-제한된-브라우저의-페이지는-어떻게-처리합니까-어떤-기술-프로세스를-사용하십니까)
* [콘텐츠를 시각적으로 숨기고(화면 판독기에서만 사용할 수 있게 만드는)다양한 방법은 무엇입니까?](#콘텐츠를-시각적으로-숨기고-화면-판독기에서만-사용할-수-있게-만드는-다양한-방법은-무엇입니까)
* [혹시 그리드 시스템을 사용하나요? 만약 그렇다면, 당신은 어떤것을 선호합니까?](#혹시-그리드-시스템을-사용하나요-만약-그렇다면-당신은-어떤것을-선호합니까)
* [미디어 쿼리 또는 모바일 관련 layouts/CSS 를 사용하거나 구현해 보았습니까?](#미디어-쿼리-또는-모바일-관련-layouts-CSS를-사용하거나-구현해-보았습니까)
* [SVG-스타일링에-익숙하십니까?](#SVG-스타일링에-익숙하십니까)
* [screen 이 아닌 @media 속성의 예를 들려 줄 수 있습니까?](#screen이-아닌-@media-속성의-예를-들려-줄-수-있습니까)
* [효율적인 CSS 를 작성하는데 있어 "어려움"은 무엇입니까?](#효율적인-CSS를-작성하는데-있어-"어려움"은-무엇입니까)
* [CSS 전처리기를 사용하면 어떤 장단점이 있습니까?](#CSS-전처리기를-사용하면-어떤-장단점이-있습니까)
* [사용했던 CSS 전처리기에 대해 좋아하는 것과 싫어하는 것을 설명하십시오.](#사용했던-CSS-전처리기에-대해-좋아하는-것과-싫어하는-것을-설명하십시오)
* [비표준 글꼴을 사용하는 웹 디자인 디자인을 구현하는 방법은 무엇입니까?](#비표준-글꼴을-사용하는-웹-디자인-디자인을-구현하는-방법은-무엇입니까)
* [CSS 셀렉터에 일치하는 요소가 어떤 것인지 브라우저가 어떻게 결정되는지를 설명하시오.](#CSS-셀렉터에-일치하는-요소가-어떤-것인지-브라우저가-어떻게-결정되는지를-설명하시오)
* [Pseudo-elements 에 대해 설명하고 그 요소가 무엇을 위해 사용되는지 설명하시오.](#pseudo-elements에-대해-설명하고-그-요소가-무엇을-위해-사용되는지-설명하시오)
* [박스 모델에 대한 이해와 CSS 에서 브라우저에 다른 박스 모델로 레이아웃을 렌더링하는 방법을 설명하십시오.](#박스-모델에-대한-이해와-CSS-에서-브라우저에-다른-박스-모델로-레이아웃을-렌더링하는-방법을-설명하십시오)
* [`* { box-sizing: border-box; }` 는 무엇을 하나요? 장점은 무엇입니까?](#box-sizing-border-box-는-무엇을-하나요-장점은-무엇입니까)
* [CSS 의 `display` 속성은 무엇이며 사용법에 대한 몇 가지 예를 들 수 있습니까?](#CSS의-display-속성은-무엇이며-사용법에-대한-몇-가지-예를-들-수-있습니까)
* [`inline` 과 `inline-block` 의 차이점은 무엇입니까?](#inline-과-inline-block-의-차이점은-무엇입니까)
* [`relative`, `fixed`, `absolute` 와 `static` 요소의 차이점은 무엇입니까?](#relative-fixed-absolute-와-static-요소의-차이점은-무엇입니까)
* [What existing CSS frameworks have you used locally, or in production? How would you change/improve them?](#what-existing-css-frameworks-have-you-used-locally-or-in-production-how-would-you-changeimprove-them)
* [Have you played around with the new CSS Flexbox or Grid specs?](#have-you-played-around-with-the-new-css-flexbox-or-grid-specs)
* [Can you explain the difference between coding a web site to be responsive versus using a mobile-first strategy?](#can-you-explain-the-difference-between-coding-a-web-site-to-be-responsive-versus-using-a-mobile-first-strategy)
* [Have you ever worked with retina graphics? If so, when and what techniques did you use?](#have-you-ever-worked-with-retina-graphics-if-so-when-and-what-techniques-did-you-use)
* [Is there any reason you'd want to use `translate()` instead of `absolute` positioning, or vice-versa? And why?](#is-there-any-reason-youd-want-to-use-translate-instead-of-absolute-positioning-or-vice-versa-and-why)

---

## CSS 질문

[프론트엔드 면접 질문 - CSS 질문](https://github.com/h5bp/Front-end-Developer-Interview-Questions#css-questions)에 대한 해설입니다.
Pull Request 를 통한 제안 및 수정 요청을 환영합니다.

### CSS 선택자 특이성은 무엇이며 어떻게 작동합니까?

브라우저는 CSS 규칙의 특수성에 따라 요소에 표시할 스타일을 결정합니다. 브라우저는 이미 특정 요소와 일치하는 규칙을 결정했다고 가정합니다. 일치하는 규칙들 가운데, 다음에 기초하여 각 규칙에 대해 특수성, 네개의 쉼표로 구분된 값,`a, b, c, d`가 계산됩니다.

1.  `a`는 인라인 스타일이 사용되고 있는지 여부입니다. 속성 선언이 요소에서 인라인 스타일이면 'a'는 1 이고, 그렇지 않으면 0 입니다.
2.  `b`는 ID 셀렉터의 수입니다.
3.  `c`는 클래스, 속성 및 가상 클래스 선택자의 수입니다.
4.  `d`는 태그 및 유사 요소 선택자의 수입니다.

결과적인 특정성은 점수가 아니라, 컬럼마다 비교할 수 있는 가치들의 행렬입니다. 선택자를 비교하여 가장 높은 특이성을 갖는 항목을 결정할 때 왼쪽에서 오른쪽으로 보고 각 열의 가장 높은 값을 비교하세요. 따라서 `b`열의 값은 `c`와 `d`열에 있는 값을 무시합니다. 따라서 `0,1,0,0`의 특이성은 `0,0,10,10`중 하나보다 큽니다.

동등한 특이성의 경우: 최신 규칙은 중요한 규칙입니다. 스타일 시트에 동일한 규칙을 두 번 작성한 경우(내부나 외부에 관계 없이) 스타일 시트의 하위 규칙이 스타일 될 요소에 더 가까우므로 더 구체적으로 적용됩니다.

필자는 필요하다면 쉽게 재정의할 수 있도록 낮은 특정성 규칙들을 작성할 것입니다. CSS UI 컴포넌트 라이브러리 코드를 작성할 때 특이성을 높이거나 `!important`를 사용하기 위해 라이브러리 사용자가 지나치게 복잡한 CSS 규칙을 사용하지 않고도 이를 무시할 수 있도록 특이성이 낮은 것이 중요합니다.

###### 참고자료

* <https://www.smashingmagazine.com/2007/07/css-specificity-things-you-should-know/>
* <https://www.sitepoint.com/web-foundations/specificity/>

### "Resetting"과 "Normalizing" CSS 의 차이점은 무엇입니까? 당신은 무엇을 선택할 것이며, 그 이유는 무엇입니까?

* **Resetting** - Resetting 은 요소의 모든 기본 브라우저 스타일을 제거하기 위한 것입니다. 예 : `margin`, `padding`s,`font-size`는 같은 값으로 재설정됩니다. 일반적인 타이포그래피 요소에 대한 스타일을 재 선언해야합니다.

* **Normalizing** - Normalizing 는 모든 것을 "정리"하는 것이 아니라 유용한 기본 스타일을 보존합니다. 또한 일반적인 브라우저 종속성에 대한 버그를 수정합니다.

필자는 나만의 스타일링을 많이 해야 하고 보존할 기본 스타일링이 필요하지 않도록 매우 맞춤화되었거나 자유로운 사이트 디자인을 가지고 있을 때 리셋을 선택합니다.

###### 참고자료

* <https://stackoverflow.com/questions/6887336/what-is-the-difference-between-normalize-css-and-reset-css>

### `float`이 어떻게 작동하는지 설명하세요.

Float 은 CSS 위치 지정 속성입니다. Float 된 요소는 페이지의 흐름의 일부로 남아 있으며 페이지의 흐름에서 제거되는 'position : absolute'요소와 달리 다른 요소 (예 : 플로팅 요소 주위로 텍스트가 흐르게 됨)의 위치 지정에 영향을 줍니다.

CSS `clear` 속성은`left`/`right`/`both` float 엘리먼트 아래에 위치하도록 사용될 수 있습니다.

부모 요소에 float 된 요소만 있으면 그 높이가 무효로 됩니다. 컨테이너의 플로팅 된 요소 다음에 있지만 컨테이너가 닫히기 전에 float 를 clear 하면 해결할 수 있습니다.

`.clearfix` 핵은 영리한 CSS 의사 선택자 (`: after`)를 사용하여 실수를 제거합니다. 상위 클래스에 overflow 를 설정하는 대신 추가 클래스 `clearfix`를 적용합니다. 그런 다음이 CSS 를 적용하십시오:

```css
.clearfix:after {
  content: ' ';
  visibility: hidden;
  display: block;
  height: 0;
  clear: both;
}
```

양자택일로, 부모 요소에 `overflow : auto` 또는 `overflow : hidden` 속성을 주면 자식 요소 내부에 새로운 블록 형식화 문맥을 설정하고 자식을 포함하도록 확장합니다.

###### 참고자료

* <https://css-tricks.com/all-about-floats/>

### `z-index`와 쌓임 맥락(stacking context)이 어떻게 형성되는지 설명하세요.

CSS 의 `z-index`속성은 요소의 겹치는 요소의 순서를 제어합니다. `z-index`는 `static`이 아닌 `position` 값을 갖는 요소에만 영향을 줍니다.

`z-index` 값이 없으면 DOM 에 나타나는 순서대로 요소가 쌓이게 됩니다 (동일한 레이어에서 가장 낮은 레이어의 맨 위에 나타납니다). 정적이지 않은(non-static) 위치 지정 요소 (및 해당 하위 요소)는 HTML 레이어 구조와 상관없이 기본 정적 위치 지정을 사용하여 항상 요소 위에 나타납니다.

쌓임 맥락(stacking context)은 레이어 집합을 포함하는 요소입니다. 쌓임 맥락(stacking context) 지역 내에서 자식의 `z-index` 값은 문서 루트가 아닌 해당 요소를 기준으로 설정됩니다. 해당 컨텍스트 외부의 레이어 — 즉 로컬 쌓임 맥락의 형제 요소 — 그 사이의 레이어에 어울릴 수 없습니다. 요소 B 가 요소 A 의 상단에 위치하는 경우, 요소 A 의 하위 요소 C 는 요소 C 가 요소 B 보다 `z-index`가 더 높은 경우에도 요소 B 보다 높을 수 없습니다.

각각의 쌓임 맥락은 자체적으로 포함되어 있습니다 - 요소의 내용이 쌓인 후에는 전체 요소를 쌓임 맥락의 쌓인 순서로 고려합니다. 소수의 CSS 속성이 `opacity`가 1 보다 작고 `filter`가 `none`이 아니며 `transform`이 `none`이 아닌 새롭게 쌓임 맥락(stacking context)을 트리거합니다.

###### 참고 자료

* <https://css-tricks.com/almanac/properties/z/z-index/>
* <https://philipwalton.com/articles/what-no-one-told-you-about-z-index/>
* <https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Positioning/Understanding_z_index/The_stacking_context>

### 블록 서식 문맥(BFC)과 작동 방식을 설명하세요.

BFC(블록 서식 문맥)는 블록 박스가 배치된 웹 페이지의 시각적 CSS 렌더링의 일부입니다. Floats, absolutely positioned elements, `inline-blocks`, `table-cells`, `table-caption`s, and elements with `overflow` other than `visible` (그 값이 viewport 에 전파되었을 때는 제외) establish new block formatting contexts.

BFC 는 다음 조건 중 하나 이상을 충족시키는 HTML 박스입니다:

* `float`의 값은 `none`이 아닙니다.
* `position`의 값은 `static`도 아니고 `relative`도 아닙니다.
* `display`의 값은 `table-cell`, `table-caption`, `inline-block`, `flex` 또는 `inline-flex`입니다.
* `overflow`의 값은 `visible`이 아닙니다.

BFC 에서 각 박스의 왼쪽 바깥 가장자리는 포함하는 블록의 왼쪽 가장자리에 닿습니다 (오른쪽에서 왼쪽으로 포맷팅, 오른쪽 가장자리에서 터치).

BFC 상쇄(collapse)시 인접한 블록 레벨 박스 사이의 Vertical 마진. [마진 collapsing](https://www.sitepoint.com/web-foundations/collapsing-margins/)에 대해 자세히 읽어보세요.

###### 참고 자료

* <https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Block_formatting_context>
* <https://www.sitepoint.com/understanding-block-formatting-contexts-in-css/>

### clear 하는 방법에는 어떤 것이 있으며, 각각 어떤상황에 적합합니까?

* 비어있는 `div` 방법 - `<div style="clear:both;"></div>`
* Clearfix 방법 - 이와 같은 `.clearfix` 클래스를 참조하세요.
* `overflow: auto` 또는 `overflow: hidden` 방법 - 부모는 새로운 블록 서식 지정 컨텍스트를 설정하고, 확장 된 자식을 포함하도록합니다.

대규모의 프로젝트에서는 유용하게 `.clearfix` 클래스를 만들어 필요한 곳에서 사용합니다. 자식이 부모보다 크기가 경우 `overflow: hidden`은 자식의 모두 보여줄 수 없습니다.

### CSS 스프라이트는 무엇입니까? 그리고 당신이 페이지 나 사이트에 구현하는 방법도 설명해주세요.

CSS 스프라이트는 여러 이미지를 하나의 큰 이미지로 결합합니다. 일반적으로 아이콘에 사용되는 기술(Gmail 에서 사용)입니다. 구현방법:

1.  스프라이트 생성기를 사용하여 여러 이미지를 하나로 묶어 적절한 CSS 를 생성합니다.
2.  각 이미지는`background-image`,`background-position` 및`background-size` 속성이 정의 된 해당 CSS 클래스를 갖습니다.
3.  해당 이미지를 사용하려면 요소에 해당 클래스를 추가하십시오.

**장점:**

* 여러 이미지에 대한 HTTP 요청 수 줄이기(스프라이트 시트 당 하나의 단일 요청 만 필요합니다.) 그러나 HTTP2 를 사용하면 여러 이미지를로드하는 것이 더 이상 중요하지 않습니다.
* `: hover`의 상태에서만 나타나는 이미지가 필요할 때 다운로드되지 않는 이미지를 미리 다운로드하여 깜박임이 보이지 않습니다.

###### 참고 자료

* <https://css-tricks.com/css-sprites/>

### 브라우저 별 스타일링 문제를 해결하는 방법에 대해 어떻게 생각하십니까?

* 문제 및 문제를 일으키는 브라우저를 식별한 후에는 해당 브라우저가 사용 중일 때만 로드되는 별도의 스타일 시트를 사용하십시오. 하지만 이 기술을 사용하려면 서버 측 렌더링이 필요합니다.
* 이미 이러한 스타일링 문제를 처리하고 있는 Bootstrap 과 같은 라이브러리를 사용하십시오.
* `autoprefixer`를 사용하여 벤더 프리픽스를 코드에 자동으로 추가하십시오.
* Reset CSS 또는 Normalize.css 를 사용합니다.

### 기능이 제한된 브라우저의 페이지는 어떻게 처리합니까? 어떤 기술/프로세스를 사용하십니까?

* 우아한 퇴화 - 최신 브라우저를 위한 응용 프로그램을 구축하는 동시에 그것이 구형 브라우저에서도 계속 작동하도록 하는 구축방법.
* 점진적 향상 - 기본 수준의 사용자 환경에 대한 응용 프로그램을 구축하지만 브라우저가 이를 지원할 경우 기능을 강화하는 방법이 있습니다.
* [caniuse.com](https://caniuse.com/)을 사용하여 기능 지원을 확인하십시오.
* 자동 공급 프리픽스인 Autoprefixer 삽입.
* [Modernizr](https://modernizr.com/)를 사용하여 미래 간파.

### 콘텐츠를 시각적으로 숨기고(화면 판독기에서만 사용할 수 있게 만드는)다양한 방법은 무엇입니까?

이러한 기술은 접근성 (a11y)에 관련이 있습니다.

* `visibility: hidden`. 그러나 요소는 아직 페이지의 흐름에 여전히 공간을 차지하고 있습니다.
* `width: 0; height: 0`. 요소가 화면의 어떤 공간도 차지하지 않도록하십시오. 결과적으로 보이지 않습니다.
* `position: absolute; left: -99999px`. 화면 외부에 배치합니다.
* `text-indent: -9999px`. 이것은 `block`인 엘리먼트 내의 텍스트에서만 작동합니다.
* 메타 데이터. 예를 들어, Schema.org, RDF 및 JSON-LD 를 사용합니다.
* WAI-ARIA. 웹 페이지의 액세스 가능성을 높이는 방법을 지정하는 W3C 기술 사양입니다.

WAI-ARIA 가 이상적인 해결책이라 하더라도, 저는 `absolute` 접근법을 택할 것입니다. 대부분요소에 적용되고, 쉽고 주의해야할 것이 가장 적습니다.

###### 참고자료

* <https://www.w3.org/TR/wai-aria-1.1/>
* <https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA>
* <http://a11yproject.com/>

### 혹시 그리드 시스템을 사용하나요? 만약 그렇다면, 당신은 어떤것을 선호합니까?

나는 `float` 기반 그리드 시스템을 좋아한다. 왜냐하면 여전히 기존의 다른 시스템들(flex, grid) 중에서도 가장 많은 브라우저를 지원하기 때문입니다. 이것은 부트 스트랩에서 수년 동안 사용되었으며, 효과가 있다는 것이 입증되었습니다.

### 미디어 쿼리 또는 모바일 관련 layouts/CSS 를 사용하거나 구현해 보았습니까?

네. 한가지 예를 들면 여러 줄 형식의 네비게이션을 중간시점이 지나면 텝의 형태로 변환하였습니다.

### SVG 스타일링에 익숙하십니까?

슬프게도 아니요...

### screen 이 아닌 @media 속성의 예를 들려 줄 수 있습니까?

예, @ media 속성을 screen 포함하여 4 가지 종류가 있습니다. :

* all - for all media type devices
* print - for printers
* speech - for screenreaders that "reads"the page out loud
* screen - for computer screens, tablets, smart-phones etc.
* print 미디어 유형의 사용 예제 :

```css
@media print {
  body {
    color: black;
  }
}
```

### 효율적인 CSS 를 작성하는데 있어 "어려움"은 무엇입니까?

먼저 브라우저는 오른쪽선택자에서 왼쪽으로 선택자가 일치하는지 확인합니다. 브라우저는 선택자에 따라 DOM 의 요소를 필터링하고 해당 부모요소가 일치하는지 식별합니다. 선택자 체인의 길이가 짧을수록 브라우저는 해당 요소가 선택자와 일치하는지 여부를 빠르게 판별할 수 있습니다. 따라서 태그선택자와 보편적인 선택자자를 사용하지마세요. 그것들은 다수의 요소가 브라우저와 매치되기 때문에 부모가 일치하는지 여부를 판단하기 위해 많은 작업을 해야합니다.

[BEM (Block Element Modifier)](https://bem.info/)의 방법론에서는 모두 단일 클래스를 갖고, 계층구조가 필요한 곳에서는 클래스의 이름이 확장되기를 권장합니다. 따라서 선택자를 쉽고 효율적으로 재정의 할 수 있습니다.

어떠한 CSS 속성이 리플로우또는 합성되는 것을 주의 하십시오. 가능하다면 레이아웃을 변경하는 스타일링(리플로우를 작동시키는 스타일)은 작성하지 마십시오.g styles that change the layout (trigger reflow) where possible.

###### 참고 자료

* <https://developers.google.com/web/fundamentals/performance/rendering/>
* <https://csstriggers.com/>

### CSS 전처리기를 사용하면 어떤 장단점이 있습니까?

**장점:**

* CSS 의 유지보수성 향상됩니다.
* 중첩된 선택자를 작성하기 쉽습니다.
* 일관된 스타일링 설정을 위한 변수사용. 여러 프로젝트에 걸쳐 테마 파일을 공유할 수 있습니다.
* 반복되는 CSS 를 위한 Mixins 생성.
* 코드를 여러 파일로 나눕니다. CSS 파일도 나눌 수 있지만, 그렇게 하기 위해서는 각 CSS 파일을 다운로드하기 위한 HTTP 요청이 필요합니다.

**단점:**

* 전처리기를 위한 도구가 필요합니다. 다시 컴파일하는 시간이 느릴 수 있습니다.

### 사용했던 CSS 전처리기에 대해 좋아하는 것과 싫어하는 것을 설명하십시오.

**좋은것:**

* 대부분 위에서 언급 한 장점이 있습니다..
* Less 는 자바 스크립트로 작성되었으며 Node 와 잘 작동합니다.

**싫은것:**

* 나는 C++로 작성된 LibSass 를 바인딩인 'node-sass'를 통해 Sass 를 사용합니다. 노드 버전이 바뀔 때 자주 다시 컴파일해야합니다.
* Less 에서는 변수 이름의 접두어가`@`로되어 있으며, `@media`, `@import` 및 `@font-face` 규칙과 같은 고유 CSS 키워드와 혼동 될 수 있습니다.

### 비표준 글꼴을 사용하는 웹 디자인 디자인을 구현하는 방법은 무엇입니까?

`font-face`를 사용하고 `font-weight`가 다른 경우 `font-family`를 정의합니다.

### CSS 셀렉터에 일치하는 요소가 어떤 것인지 브라우저가 어떻게 결정되는지를 설명하시오.

이 부분은 위의 효율적인 CSS 작성에 대한 것입니다. 브라우저는 셀렉터를 오른쪽(선택자)에서 왼쪽으로 일치시킵니다. 브라우저는 선택자에 따라 DOM 의 요소를 필터링하고 부모 요소를 검사하여 일치를 판정합니다. 선택자 체인의 길이가 짧을수록, 브라우저가 해당 요소가 선택기에 일치하는지 여부를 판단 할 수 있습니다.

예를 들어,이 셀렉터 `p span`는 브라우저는 먼저 모든 `<span>`요소를 찾아 그 부모의 루트까지 모두 통과하여 `<p>`요소를 찾습니다. 특정한 `<span>`의 경우 `<p>`를 찾는 즉시 `<span>`이 일치하는 것을 알고 있으며, 그에 따라 매칭 중지합니다.

###### 참고자료

* <https://stackoverflow.com/questions/5797014/why-do-browsers-match-css-selectors-from-right-to-left>

### Pseudo-elements 에 대해 설명하고 그 요소가 무엇을 위해 사용되는지 설명하시오.

CSS Pseudo-element 는 Selector 에 추가 된 키워드로, 선택한 요소의 특정한 부분을 스타일링 할 수 있습니다. 마크업을 수정하지 않고 (`:before`, `:after`) 텍스트 데코레이션을 위해 사용하거나 (`:first-line`, `:first-letter`) 또는 마크 업에 요소를 추가할 수 있습니다. (`content: ...` 와 결합)

* `:first-line` 과 `:first-letter` 는 텍스트를 데코레이션하는데 사용될 수 있습니다.
* 위와 같이 `.clearfix` 에 사용되어 `clear: both` 로 영역을 차지하지 않는 요소를 추가합니다.
* 툴팁의 삼각형 화살표는 `:before` 와 `:after` 를 사용합니다. 삼각형이 실제로 DOM 이 아닌 스타일의 일부로 간주되기 때문에 분리하는 것이 좋습니다. 추가적인 HTML 요소를 사용하지 않고 CSS 스타일만으로 삼각형을 그릴 수는 없습니다.

###### 참고자료

* <https://css-tricks.com/almanac/selectors/a/after-and-before/>

### 박스 모델에 대한 이해와 CSS 에서 브라우저에 다른 박스 모델로 레이아웃을 렌더링하는 방법을 설명하십시오.

CSS 박스 모델은 문서 트리의 요소에 대해 생성되고 시각적 서식 모델에 따라 배치된 사각형 상자를 나타냅니다. 각 박스에는 content 영역 (예: 텍스트, 이미지 등) 및 선택적 주변의 'padding', 'border' 및 'margin' 영역이 있습니다.

CSS 박스 모델은 다음을 계산합니다.

* 블록 요소가 차지하는 공간.
* 테두리 또는 여백이 겹치거나 붕괴되는지 여부.
* 박스의 크기.

박스 모델에는 다음과 같은 규칙이 있습니다.

* 블록 요소의 크기는 `width`, `height`, `padding`, `border`, `margin`에 의해 계산됩니다.
* `height` 가 지정되어 있지 않은 경우, 블럭 요소는 포함하고있는 내용만큼의 높이를 가질 것이고, `padding` 을 덧붙일 것입니다(아래에 float 가 없다면).
* `width` 가 지정되지 않으면, float 가 아닌 블록 요소는 (부모의 너비 - `padding`) 에 맞게 확장됩니다.
* 요소의 `height`는 내용의 `height`에 의해 계산됩니다.
* 요소의 `width`는 내용의 `width`에 의해 계산됩니다.
* 기본적으로 `padding`과 `border`는 요소의 `width`와 `height`의 일부가 아닙니다.

###### 참고자료

* <https://www.smashingmagazine.com/2010/06/the-principles-of-cross-browser-css-coding/#understand-the-css-box-model>

### `* { box-sizing: border-box; }` 는 무엇을 하나요? 장점은 무엇입니까?

* 기본적으로, 요소들은 `box-sizing: content-box`가 적용되고, 내용의 크기 만 고려됩니다.
* `box-sizing: border-box` 는 요소의 `width` 와 `height` 가 어떻게 계산되는지를 변경하여 `border` 와 `padding` 도 계산에 포함됩니다.
* 요소의 `height` 는 내용의 `height` + 수직 `padding` + 수직 `border` 폭에 의해 계산됩니다.
* 요소의 `width` 는 내용의 `width` + 수평 `padding` + 수평 `border` 폭에 의해 계산됩니다.

### CSS 의 `display` 속성은 무엇이며 사용법에 대한 몇 가지 예를 들 수 있습니까?

* `none`, `block`, `inline`, `inline-block`, `table`, `table-row`, `table-cell`, `list-item`.

TODO

### `inline` 과 `inline-block` 의 차이점은 무엇입니까?

좋은 비교를 위해 `block` 과도 비교해 볼 것입니다.

|                                  | `block`                                                                                     | `inline-block`                                                   | `inline`                                                                                                                                                                          |
| -------------------------------- | ------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 크기                             | 부모 컨테이너의 너비를 채 웁니다.                                                           | 내용에 따라 달라집니다.                                          | 내용에 따라 달라집니다.                                                                                                                                                           |
| 위치                             | 새 줄에서 시작하고 그 옆에 HTML 요소를 허용하지 않습니다 (`float`을 추가 할 때를 제외하고). | 다른 콘텐츠와 함께 흐르고 다른 요소는 옆에 있는 것을 허용합니다. | F 다른 콘텐츠와 함께 흐르고 다른 요소는 옆에 있는 것을 허용합니다.                                                                                                                |
| `width`, `height` 지정 가능 여부 | 가능                                                                                        | 가능                                                             | 불가능. 설정되면 무시됩니다.                                                                                                                                                      |
| `vertical-align` 정렬 가능 여부  | 불가능                                                                                      | 불가능                                                           | 불가능                                                                                                                                                                            |
| margin 및 padding                | 모든방향에서 가능.                                                                          | 모든방향에서 가능.                                               | 수평방향만 가능. 세로방향을 지정하면 레이아웃에 영향을 주지 않습니다. `border` 와 `padding` 이 콘텐츠 주위에 시각적으로 나타나는 경우에도 수직영역은 `line-height` 에 의존합니다. |

Becomes like a `block` element where you can set vertical margins and paddings.
| Float | - | - | 수직 margin 과 padding 을 설정할 수 있는 `block` 엘리먼트와 같습니다. |

### `relative`, `fixed`, `absolute` 와 `static` 요소의 차이점은 무엇입니까?

위치가 정해진 요소는 계산된 `position` 속성이 `relative`, `absolute`, `fixed` 또는 `sticky`인 요소입니다.

* `static` - 기본 위치. 요소는 평소와 같이 페이지에 위치합니다. `top`, `right`, `bottom`, `left` 및 `z-index` 속성은 적용되지 않습니다.
* `relative` - 요소의 위치는 레이아웃을 변경하지 않고 자체에 상대적으로 조정됩니다. (따라서 배치되지 않은 요소의 간격을 남겨 둡니다.)
* `absolute` - 요소는 페이지의 평소 위치에서 제거되고 가장 가까운 위치에 `relative` 부모 블록이 있는 경우 지정된 위치에 배치됩니다. 그렇지 않으면 최상위 블록과 관련됩니다. absolute 로 배치된 박스는 여백을 가질 수 있으며 다른 여백과 충돌하지 않습니다. 이 요소는 다른 요소의 위치에 영향을 주지 않습니다.
* `fixed` - 요소는 페이지의 평소 위치에서 제거되고 뷰포트를 기준으로 지정된 위치에 배치되며 스크롤 할 때 이동하지 않습니다.
* `sticky` - 스티키 포지셔닝은 `relative` 와 `fixed` 의 하이브리드입니다. 요소는 지정된 임계 값을 넘을 때까지 `상대적` 위치로 처리되며, 특정 지점에서 `고정된` 위치로 처리됩니다.

###### 참고자료

* <https://developer.mozilla.org/en/docs/Web/CSS/position>

### What existing CSS frameworks have you used locally, or in production? How would you change/improve them?

* **Bootstrap** - Slow release cycle. Bootstrap 4 has been in alpha for almost 2 years. Add a spinner button component, as it is widely-used.
* **Semantic UI** - Source code structure makes theme customization extremely hard to understand. Painful to customize with unconventional theming system. Hardcoded config path within the vendor library. Not well-designed for overriding variables unlike in Bootstrap.
* **Bulma** - A lot of non-semantic and superfluous classes and markup required. Not backward compatible. Upgrading versions breaks the app in subtle manners.

### Have you played around with the new CSS Flexbox or Grid specs?

Yes. Flexbox is mainly meant for 1-dimensional layouts while Grid is meant for 2-dimensional layouts.

Flexbox solves many common problems in CSS, such as vertical centering of elements within a container, sticky footer, etc. Bootstrap and Bulma are based on Flexbox, and it is probably the recommended way to create layouts these days. Have tried Flexbox before but ran into some browser incompatibility issues (Safari) in using `flex-grow`, and I had to rewrite my code using `inline-blocks` and math to calculate the widths in percentages, it wasn't a nice experience.

Grid is by far the most intuitive approach for creating grid-based layouts (it better be!) but browser support is not wide at the moment.

###### References

* <https://philipwalton.github.io/solved-by-flexbox/>

### Can you explain the difference between coding a web site to be responsive versus using a mobile-first strategy?

TODO

### How is responsive design different from adaptive design?

Both responsive and adaptive design attempt to optimize the user experience across different devices, adjusting for different viewport sizes, resolutions, usage contexts, control mechanisms, and so on.

Responsive design works on the principle of flexibility - a single fluid website that can look good on any device. Responsive websites use media queries, flexible grids, and responsive images to create a user experience that flexes and changes based on a multitude of factors. Like a single ball growing or shrinking to fit through several different hoops.

Adaptive design is more like the modern definition of progressive enhancement. Instead of one flexible design, adaptive design detects the device and other features, and then provides the appropriate feature and layout based on a predefined set of viewport sizes and other characteristics. The site detects the type of device used, and delivers the pre-set layout for that device. Instead of a single ball going through several different-sized hoops, you'd have several different balls to use depending on the hoop size.

###### References

* <https://developer.mozilla.org/en-US/docs/Archive/Apps/Design/UI_layout_basics/Responsive_design_versus_adaptive_design>
* <http://mediumwell.com/responsive-adaptive-mobile/>
* <https://css-tricks.com/the-difference-between-responsive-and-adaptive-design/>

### Have you ever worked with retina graphics? If so, when and what techniques did you use?

I tend to use higher resolution graphics (twice the display size) to handle retina display. The better way would be to use a media query like `@media only screen and (min-device-pixel-ratio: 2) { ... }` and change the `background-image`.

For icons, I would also opt to use svgs and icon fonts where possible, as they render very crisply regardless of resolution.

Another method would be to use JavaScript to replace the `<img>` `src` attribute with higher resolution versions after checking the `window.devicePixelRatio` value.

###### References

* <https://www.sitepoint.com/css-techniques-for-retina-displays/>

### Is there any reason you'd want to use `translate()` instead of `absolute` positioning, or vice-versa? And why?

`translate()` is a value of CSS `transform`. Changing `transform` or `opacity` does not trigger browser reflow or repaint, only compositions, whereas changing the absolute positioning triggers `reflow`. `transform` causes the browser to create a GPU layer for the element but changing absolute positioning properties uses the CPU. Hence `translate()` is more efficient and will result in shorter paint times for smoother animations.

When using `translate()`, the element still takes up its original space (sort of like `position: relative`), unlike in changing the absolute positioning.

###### References

* <https://www.paulirish.com/2012/why-moving-elements-with-translate-is-better-than-posabs-topleft/>

### Other Answers

* <https://neal.codes/blog/front-end-interview-css-questions>
* <https://quizlet.com/28293152/front-end-interview-questions-css-flash-cards/>
* <http://peterdoes.it/2015/12/03/a-personal-exercise-front-end-job-interview-questions-and-my-answers-all/>
