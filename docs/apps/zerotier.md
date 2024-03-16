---
title: ZeroTierOne
---

# ZeroTierOne

ZeroTierOne — бесплатный, с открытым исходным кодом, мультиплатформенный, приватный-безопасный сервис для создания виртуальных сетей. Позволяет присоединить все свои устройства в одну сеть. Один из вариантов использования, многопользовательский режим по сети в играх, в которых есть только LAN-поддержка.

## Установка из репозитория

::: code-group

```shell[apt-get]
su -
apt-get update
apt-get install zerotier-one
```
```shell[epm]
epm -i zerotier-one
```
:::

После установки **ZeroTierOne**, необходимо добавить и запустить службу для начала использования приложения в системе:

```shell
su -
serv zerotier-one on
```