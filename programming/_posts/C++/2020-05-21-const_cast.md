---
layout: post
title: "[C++문법]const_cast와 mutable"
description: >
    [C++문법]상수성을 제거하는 const_cast와, 상수 멤버 함수 내에서도 수정할 수 있는 mutable
author: author1
category: [C++]
---
### 1. const_cast
- __<span style="color: var(--highlight-color)"> const_cast<바꿀 타입>(대상) </span>__   
- const로 정의된 변수의 상수성을 제거해주는데 사용