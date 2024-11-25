---
order: 15
authors:
  - Sharikfi
---

# Подключение домена к Cloudflare

[[toc]]

Для использования Cloudflare с вашим доменом, войдите в панель управления Cloudflare и нажмите "Add a Domain".

![add](/host/domain/1.png)

Введите доменное имя и нажмите "Continue". Выберите тарифный план. В разделе "Your assigned Cloudflare nameservers" скопируйте предоставленные адреса DNS-серверов. Затем войдите в панель управления вашим доменом и найдите раздел для изменения DNS-серверов (или именных серверов).

Удалите существующие DNS-серверы, предоставленные вашим регистратором, и сохраните изменения, указав скопированные адреса DNS-серверов Cloudflare.

![nameservers](/host/domain/2.png)

:::info Важно
Ожидайте пока ваш регистратор не сменит DNS-сервера (обычно это занимает до 24 часов).
:::