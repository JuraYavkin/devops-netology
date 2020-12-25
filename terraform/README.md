## Описание файла .gitignore для папки terraform

```**/.terraform/*```

Будут проигнорированы все папки .terraform и файлы(как и папки) в них (например a/.terraform/test.txt, a/b/.terraform/test.txt и т.д.) 

```
*.tfstate
*.tfstate.*
```

Файлы с расширением .tfstate и .tfstate.xxx

```
crash.log
```

Конкретный файл crash.log
```
*.tfvars
```

Файлы с расширением .tfvars
```
override.tf
override.tf.json
```

Конкретные файлы override.tf и override.tf.json
```
*_override.tf
*_override.tf.json
```

Файлы оканчивающиеся на _override.tf и _override.tf.json

```
.terraformrc
terraform.rc
```

Конкретные файлы .terraformrc и terraform.rc