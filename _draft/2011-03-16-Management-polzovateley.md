---
layout: post
title: Менеджмент пользователей
categories:
- it
---
Возникла идея - заводить всех пользователей в одном месте - на сервере? через консоль PowerShell. А уже оттуда - рассылаться на все остальные сервисы, требующие регистрации. Это и почта, и IP-телефония, и 1С.

Как инструмент для реализации данного функционала я выбрал PowerShell и набор командлетов NetCmdlets v3.

Идея в том чтобы запускать скрипт с параметрами, который создаст пользователя на сервере, пользователя в LDAP, пользователя в MySQL, создаст файл настроек для копоративного почтового клиента и отправит учётные с файлом настроек админу в почту.