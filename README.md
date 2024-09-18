# homework-k8s

## Разворачиваем jenkins и бд для будущих плагинов и логирования в кластере k8s. Используем общий неймспейс, создаем сервисы и роли. Клонируем к себе командой git clone https://github.com/hawk0774/homework-rosatom. Переходим в директорию homework и запускаем kubectl apply -f homework-rosatom/ . После отработки манифестов можно подключаться http://node-ip:32000. 
Пароль можно обнаружить в конце журнала логирования pod, команда kubectl logs jenkins-deployment-<идентификатор pod> --namespace=jenkins-ns.
