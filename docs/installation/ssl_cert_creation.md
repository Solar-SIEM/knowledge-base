# Выпуск SSL-сертификата с помощью AD CS
Файлы SSL-сертификата ( tls.crt и tls.key ), используемые для авторизации HTTPS-соединений
компонентов Системы

Открываем Manage computer certificates

Запрашиваем новый сертификат:

![managecomputers](/assets/images/installation/ssl_cert_creation/managecomputers.png)
![enrollmentpolicy](/assets/images/installation/ssl_cert_creation/enrollmentpolicy.png)
![certificaterequest](/assets/images/installation/ssl_cert_creation/certificaterequest.png)
![properties](/assets/images/installation/ssl_cert_creation/properties.png)

Выпускаем, копируем на сервер

Преобразуем сертификаты - openssl pkcs12 -in aio-siem-1.pfx -out tls.crt -nodes

Редактируем tls.crt - копируем из него закрытый ключ в соседний файл tls.key (от begin до end)

Оставляем tls.crt в таком виде:

![certificate](/assets/images/installation/ssl_cert_creation/certificate.png)
