`host`, `end system` - конечное устройство, чаще всего пользовательское (ноутбук, телефон)

`communication link` -коммуникационный канал (провод, радио)

`packet switch` - пакетный коммутатор (передаёт пакеты между хостами). Принимает пакет от одного коммуникационного
канала и перенаправляет его на другой коммуникационный канал. `router`, `link-layer switches`

`link-layer switches` - коммутаторы канального уровня. Layer 2 OSI модели. Управляют трафиком между устройствами внутри
локальной сети (например, между компьютерами и точками доступа).

`router` - маршрутизатор. Работают на сетевом уровне (Layer 3 OSI модели). Занимаются маршрутизацией данных между
различными сетями, чаще всего находясь в ядре сети (между различными подсетями и интернетом).

`route` `path` - путь, через который проходит пакет от одного хоста к другому

`transmission rate` - скорость передачи

`Internet Service Providers` - интернет провайдер. Предоставляет пользователям и контент-провайдерам доступ к сети.
Провайдеры связаны друг с другом.

`Transmission Control Protocol` - TCP, протокол управления передачей
`Internet Protocol` - IP, интернет протокол



> Когда один хост хочет отправить данные другому хосту, он разбивает данные на сегменты и добавляет к каждому сегменту
> заголовочные байты. В итоге получается пакет.

