---
title: "My first brewing"
slug: "my-first-brewing"
date: 2021-07-14
author: "Zbyšek Zapadlík"
categories:
  - "Beer brewing"
tags:
  - "homebrewing"
draft: false
image: "05.jpg"
translationURL: "/posts/prvni-vareni/"
translationLang: "CS"
description: "Documented first brew on 8 May 2021 – recipe ALE 11° Lemondrop, HERMS system, 4 serious problems and the result: non-alcoholic beer at 1–2% ABV."
---

## My first brewing

I chose the recipe [ALE 11° Lemondrop](https://www.pivoteka-tabor.cz/recepty/summer-ale-11-lemondrop/) from Pivotéka Tábor. In the future I want to brew lagers, but for a start something lighter seemed right.

It was Saturday 8 May 2021 and I tried hard to prepare everything. The plan was to use 2 pots – one for hot water with the copper coil, one for the manifold. Using the [peristaltic pump version 1](/en/posts/peristaltic-pump-for-microbrewery/), I would recirculate wort through the coil – heating it without risk of scorching (HERMS).

---

## Problem no. 1

I started to heat up the water. Regulation was done by a quick-and-dirty PI regulator written in ESP8266 (NodeMCU). The temperature sensor cable snapped – a broken wire discovered during the process. A temporary workaround was improvised.

## Problem no. 2

After approximately 1 hour the pump broke. One of the wheels in the 3D-printed planetary gearbox cracked, likely from heat and mechanical load. Wort circulation stopped.

## Problem no. 3

The 30 mA RCD (residual current device) of the house tripped. The heating elements have significant leakage current and combined with the damp environment it was enough to trip it.

## Problem no. 4

We started to heat sparging water in the second pot using 3 ON/OFF switches manually. The 20 A circuit breaker tripped, cutting power again.

---

## Continuation

After all that chaos, things went better. Mashing was done and lautering was so fast that we had to choke the tubing to slow the flow rate. Then boiling and cooling with the copper coil. Wort was transferred into a plastic container with the yeast.

## Fermentation

Outside temperature was hitting 30 °C so reaching 18 °C at the start of fermentation was a struggle. Things were hectic and a lot of untested equipment played its part.

## Result

Beer did not ferment as expected – according to calculations there was approximately **1–2 % ABV**. The unstable mash temperatures led to poor starch conversion, leaving the yeast with little sugar.

Despite that, it turned out to be a nice beer and received a lot of praise as a **very tasty bitter non-alcoholic**.

![](./01.jpg)
![](./02.jpg)
![](./03.jpg)
![](./04.jpg)
![](./06.jpg)
![](./07.jpg)
![](./08.jpg)
![](./09.jpg)