---
layout: '[post]'
title: Koa 建置 RESTful API(1)
tags: 'node.js,javascript,koa,restful api'
date: 2018-12-14 11:50:25
---


## 為什麼需要 RESTful API

目前我所待的公司使用的網站技術是透過 Wordpress 來架設形象網站，Wordpress 本身是一個很強大的網站建置系統，但正因為他強大所以有了許多的包袱在裡面，對於不需要設計稿時可以不要這麼講究，但需要依照設計稿刻版時就會很麻煩啦，畢竟許多不需要的東西在裡面，例如：css 樣式、html 架構、還是使用 jQuery.....等等，這些都是目前想換掉的原因(其實就只是想換成框架換掉而已理由一堆XD)。

好的，竟然決定要換掉了那一定要有個新的方案，依照現在前段最熱門來說前後端分離是最流行的，這有什麼優點呢?

> 前端因為改成 SPA + MVVM 的架構所以使用者的體驗非常的好
> 前端能夠控制自我的流

## 關於 RESTful API

取自 WIKI 的說明

> 符合 REST 設計風格的 Web API 稱為 RESTful API。它從以下三個方面資源進行定義：
>
> 直觀簡短的資源位址：URI，比如：http://example.com/resources/
> 傳輸的資源：Web 服務接受與返回的網際網路媒體類型，比如：JSON，XML，YAML 等。
> 對資源的操作：Web 服務在該資源上所支援的一系列請求方法（比如：POST，GET，PUT 或 DELETE）。

更多資訊可以參考 https://ppt.cc/fKjlix
