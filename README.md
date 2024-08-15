# Devops Case

Repoda yer alan projelerin bağımlılıkları ile beraber (redis, postgresql) Docker ortamında çalıştırılması beklenmektedir. 

|                |Lang                           |Port                         |
|----------------|-------------------------------|-----------------------------|
|Result		     |`Node JS`                      |80, 5858                     |
|Vote            |`Python`                       |80                           |
|Worker          |`.Net`                         |-                            |
|PosgreSQL       |`SQL`                          |5432                         |
|Redis           |`redis`                        |6379                         |

Yukarıda tanımlanan servisler gösterilen portlardan yayına alınmaktadır. İlk 3 servisin (result, vote, worker) dockerized hale getirilmesi ve redis ve postgresql ile uyumlu şekilde çalıştırılması beklenmektedir.

## Bonus

Projede yer alan tüm servisleri içeren docker-compose.yaml dosyası yazılmalıdır.
