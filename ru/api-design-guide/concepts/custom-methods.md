# Дополнительные методы

Дополнительные методы API позволяют выполнять операции, которые нельзя выполнить средствами
 стандартных методов. Например, запустить или остановить виртуальную машину.

Для каждого сервиса доступен свой набор дополнительных методов. Списки методов приведены в
 справочниках к соответствующим API.

Сигнатура дополнительных методов отличается от сигнатуры стандартных методов. Название
 дополнительного метода указывается в URL ресурса после знака <q>:</q>. Например, метод для подключения диска:

```
POST https://compute.api.cloud.yandex.net/compute/v1/instances/e0m97h0gbq0foeuis03:attachDisk
```
