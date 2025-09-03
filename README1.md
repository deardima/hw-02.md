# Домашнее задание 2 - Мониторинг Zabbix

## Установка и настройка Zabbix Agent

### Выполненные задачи:
1. Установлен Zabbix Agent на два хоста
2. Настроена конфигурация агентов
3. Добавлены хосты в Zabbix Dashboard
4. Проверена работоспособность мониторинга

### Скриншот работы системы:
![Скриншот мониторинга Zabbix](./Screenshot%20from%202025-09-03%2021-07-31.png)

### Команды установки:
```bash
# Установка Zabbix Agent
sudo apt update
sudo apt install zabbix-agent

# Настройка конфигурации
sudo nano /etc/zabbix/zabbix_agentd.conf

# Перезапуск службы
sudo systemctl restart zabbix-agent
