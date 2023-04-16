---
layout: post
title: "Conjugate Roots"
author: "wano"
excerpt_separator: <!--more-->
tags: ['math']
use_math: true
lastmode: 2023-03-19 13:00:00
sitemap:
  changefreq: weekly
  priority: 0.5
---

A conjugate pair of roots refers to two complex roots of a polynomial with opposite imaginary parts.<!--more-->

*본 포스트에는 수식이 포함되어 있습니다. 분수 등의 수식이 정상적으로 보이지 않는 경우에는 수식을 마우스 오른쪽 버튼으로 클릭한 후 "Math Renderer"를 SVG로 바꿔주세요.*

이차방정식의 근이 복소수일 때, 허수부분의 부호가 반대인 두 근을 서로 켤레근이라고 합니다.

예를 들어, 다음과 같은 이차방정식이 주어졌다고 가정해보겠습니다.

<p style="text-align: center;">$ax^2 + bx + c = 0$ (단, $a$, $b$, $c$는 모두 실수이고, $a \neq 0$)</p>

이때 만약 이 이차방정식이 $x = \alpha + \beta i$를 근으로 가진다면, 나머지 한 근은 켤레근인 $x = \alpha - \beta i$ 형태가 됩니다.

이것을 증명하는 방법은 두 가지가 있습니다.

증명을 간단하게 하기 위해서 주어진 이차식의 양변을 $a$로 나누고 시작하겠습니다. 그리고 이 함수식을 $f(x)$라 하겠습니다.

<p style="text-align: center;">$f(x) = x^2 + px + q = 0 (단, $p=\frac{b}{a}$, $q=\frac{c}{a}$)</p>

1) $f(\alpha + \beta i) = 0$ 일 때 $f(\alpha - \beta i) = 0$이 되는 것을 증명하면 됩니다.
$f(\alpha + \beta i) = (\alpha + \beta i)^2 + p(\alpha + \beta i) + q = (\alpha^2 - \beta^2 + p \alpha + q) + (2\alpha\beta + p\beta)i = 0$

실수는 덧셈에 대해서 닫혀있기 때문에 이 식을 만족시키려면 실수부와 허수부가 모두 0이어야 합니다.

<p style="text-align: center;">$\alpha^2 - \beta^2 + p \alpha + q = 0$</p>
<p style="text-align: center;">$2\alpha\beta + p\beta = 0$</p>

이때 $f(\alpha - \beta i) = (\alpha - \beta i)^2 + p(\alpha - \beta i) + q = (\alpha^2 - \beta^2 + p \alpha + q) - (2\alpha\beta + p\beta)i = 0$ 이므로 
$f(\alpha - \beta i) = 0$이 되고, $x = \alpha - \beta i$ 또한 주어진 방정식의 해가 됩니다.

