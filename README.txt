### Для работы приставок TVIP необходимо модифицировать код index.html портала ###
### Обычно файл находится тут: /var/www/stalker_portal/c ###

### Используйте следующею каманду: ###
patch /var/www/stalker_portal/c/index.html < /Patch_to_patch/stalker560.patch


### Пример ###

# cd /var/www/stalker_portal/c
# patch index.html < stalker560.patch
patching file index.html
Hunk #1 succeeded at 16 (offset -1 lines).
Hunk #2 succeeded at 334 (offset -1 lines).

### В случае неудачи, вместо "succeeded" увидите ошибку с номером проблемной строки ###
