---
date: 2015-07-06 11:48:30+00:00
layout: post
title: 用指定語言檔案及設定來執行日文程式或遊戲
thread: 164
categories: 软件
tags:  wine 分享
---

在 Linux 下，並不需要重開機，就可以讓指定的軟體，在指定的語言環境下執行，一切只需要一行指令及一個參數「Lang」，所以就來打開終端機或建立啟動圖示吧。

**$ LANG=ja_JP.UTF-8 wine [要執行的程式位置及名稱]** 

上面的「[要執行的程式位置及名稱]」，如果是跟你目前的終端機所開啟的路徑（即 $ 前的那些字）相同位置的話，只要輸入類似 abcdefgh.exe 這類的檔名（及副檔名）就可以了。 
