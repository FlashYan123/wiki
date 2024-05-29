---
order: 2
authors:
  - f21w
---

# Подключение NeoProtect к серверу

NeoProtect - прокси сервис, аналогичный TCPShield, защищающий сервер от DDoS атак.

Бесплатный тариф подходит для серверов с онлайном меньше 30 человек. О нём и пойдёт речь.

## Возможности бесплатного тарифа

- 1 ТБ трафика в месяц
- 3 домена
- 2 точки присутствия (локации, а именно Германия и США)

::: warning :warning: Обратите внимание
**Обязательно нужен купленный домен!**
:::

## Шаг 1

Для начала, нужно зайти на сайт [neoprotect.net](https://neoprotect.net/) и зарегистрироваться

![Image 1](/assets/neo.png)

## Шаг 2

После того как вы зарегистрируетесь и окажетесь на [panel.neoprotect.net](https://panel.neoprotect.net/), нажмите на "+" и выберите тарифный план. 
Затем введите IP своего сервера, выберите локацию и добавьте свой домен.

## Шаг 3

Добавляем CNAME запись в DNS. Можно скопировать во вкладке Domains в настройках сети.

![Image 2](/assets/neo2.png)