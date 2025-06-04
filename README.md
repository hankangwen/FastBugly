# FastBugly

本文由 [简悦 SimpRead](http://ksria.com/simpread/) 转码， 原文地址 [www.cnblogs.com](https://www.cnblogs.com/flamesky/p/16719219.html)

快速接入bugly到unity，支持Unity2021（Unity5以上版本都支持,当前测试工程为2021.3.9f1）

### 使用方式
Clone工程，打开SampleScene，双击打开Sample.cs代码，把自己bugly后台的appid填入BuglyAgent.InitWithAppId ("your app id");  随后打安卓包测试即可在后台看到异常上报。

地址：[FlameskyDexive/FastBugly: 快速接入新版 Bugly 到 unity，支持 unity2021 (github.com)](https://github.com/FlameskyDexive/FastBugly)

### 初衷
鹅厂提供的官方demo工程打包后台也查不到日志，N年不更新，为此本人做了部分修改测试，提供一个快速接入工程的demo。

Unity2021因为版本原因腾讯官方工程不能使用，而且Unity2021不允许Plugins/Android出现res目录，需要打包成aar，所以改用了原生安卓sdk的aar包。

https://bugly.qq.com/v2/workbench/apps
