# SOSAFE DevOps pre-test - Conceptos

A continuación encontrarás una serie de preguntas teóricas relacionadas a algunos de los servicios básicos de AWS.

Por favor responde cada pregunta de alternativas marcando con una `[x]` donde corresponda, o redacta una respuesta en palabras en el campo indicado si así se solicita.

1. Elige 1: ¿Cuál es el tamaño mínimo de un objeto en S3?:
  ```
  [ ] 1 byte
  [ ] 1 kbyte
  [ ] 0 bytes
  [ ] 1 bit
  ```

2. Elige 1: ¿Qué servicio permite el envío y recibo de mensajes no duplicados y en orden?.
  ```
  [ ] S3
  [ ] SNS
  [ ] SQS
  [ ] SMS
  ```

3. Desarrolla: Si tienes un repositorio donde varias personas trabajan en paralelo, ¿cómo organizarías el trabajo?. ¿Existe una forma de asegurar la calidad del trabajo de todos?.
  ```
  Respuesta:
  ```

4. Elige 1 y justifica: Acabas de subir un archivo a S3, y recibes una confirmación que éste ha terminado el proceso de upload. ¿Puedes leer el archivo inmediatamente?.
  ```
  [ ] Sí
  [ ] No

  ¿Por qué?:
  ```

5. Elige 1: ¿Qué servicio está destinado a analizar y debuggear aplicaciones distribuidas, encontrar bugs y problemas de performance?:
  ```
  [ ] X-Ray
  [ ] CloudWatch
  [ ] Systems Manager
  [ ] CloudTrail
  ```

6. Elige 1: ¿Cuál es el tamaño máximo de un objeto en S3?:
  ```
  [ ] 50 GB
  [ ] 500 GB
  [ ] 5 TB
  [ ] 50 TB
  [ ] No tiene máximo
  ```

7. Desarrolla: En tus palabras ¿qué son las funciones Lambda en AWS, y qué beneficios ofrece frente a alternativas como EC2 o ECS?:
  ```
  Respuesta:
  ```

8. Elige 2: ¿Para qué sirve Route53?:
  ```
  [ ] Configuración de nombres de dominio
  [ ] Balanceo de carga
  [ ] Aseguramiento de sitios con SSL (HTTPS)
  ```

9. Elige 2: ¿Qué servicios sirven para crear infraestructura como código?:
  ```
  [ ] Chef
  [ ] Terrafom
  [ ] CloudFormation
  [ ] Ansible
  ```

10. Elige 2: ¿Qué servicio sugerirías para reducir costos de uso en S3, considerando que los archivos se pueden almacenar por mucho tiempo, y a medida que el tiempo pasa el acceso a éstos es cada vez más infrecuente?:
  ```
  [ ] S3 IOPS SSD Access
  [ ] CloudFront
  [ ] S3 Infrequent Access
  [ ] S3 One Zone Access
  [ ] Glacier
  ```

11. Elige 1: Si tu sitio web realiza cargas (uploads) de archivos pesados a AWS (más de 200mb) y la conexión a Internet de los usuarios presenta interrupciones en seguidas oportunidades, ¿qué le recomiendas al equipo de desarrollo?:
  ```
  [] Implementar un sistema de tolerancia a errores, que reintente subir el archivo completo cuando éste falle
  [] Utilizar un servicio de CDN
  [] Implementar el uso de multipart uploads
  [] Configurar una VPN entre la red local de los usuarios y AWS
  ```

12. Elige 2: ¿Qué servicios sirven para configurar discos duros en la nube?:
  ```
  [ ] ElastiCache
  [ ] EFS
  [ ] Glacier
  [ ] EBS
  ```
