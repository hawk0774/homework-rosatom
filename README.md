# homework-k8s

## Разворачиваем jenkins и бд для будущих плагинов и логирования в кластере k8s. Используем общий неймспейс, создаем сервисы и роли. После отработки манифестов можно подключаться http://node-ip:32000. 
Пароль можно обнаружить в конце журнала логирования pod, команда kubectl logs jenkins-deployment-<идентификатор pod> --namespace=jenkins-ns.
