# ports

```bash
# отправить сообщение на удаленный прорт, напр. инпут graylog
echo "hello remote port" > /dev/udp/172.18.106.159/12408

# проверить открыт/закрыт порт, смотреть exit_code
echo 1 > /dev/tcp/server/3306
```
