---
layout: post
title: $1さらに
author: azu
editURL: >-
  https://github.com/proofdict/proofdict/edit/master/dict/$1さらに--01BQ92YWWKSTXDNGWVVE10WF9T.yml
date: 2017-08-12T07:10:59.555Z
permalink: /term/01BQ92YWWKSTXDNGWVVE10WF9T
id: 01BQ92YWWKSTXDNGWVVE10WF9T
description: ''
expected: $1さらに
patterns:
  - '/([\s。、\nぁ-んァ-ヶ])更に/'
specs:
  - actual: Aは加速した、更に加速した。
    expected: Aは加速した、さらに加速した。
  - actual: 加速すると更に加速した
    expected: 加速するとさらに加速した
  - actual: 変更に加えて
    expected: 変更に加えて
tags:
  - 表記統一

---

## Description

No Description 

## Patterns

This dictionary match following patterns:

    /([\s。、\nぁ-んァ-ヶ])更に/

## Expected

The text is matched and replaced to be:

    $1さらに

## Examples

| From           | To              |
| -------------- | --------------- |
| Aは加速した、更に加速した。 | Aは加速した、さらに加速した。 |
| 加速すると更に加速した    | 加速するとさらに加速した    |
| 変更に加えて         | 変更に加えて          |
