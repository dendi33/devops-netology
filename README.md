# devops-netology
---
.gitignore 
Terraform **/.terraform/*
1. Будут прогнорированны все каталогии .terraform в рамках проекта и все файлы в нем .

*.tfstate

2. Будут проигнориированы все файлы по шаблону (ноль или более символов).tfstate во всех папках и подпапках

*.tfstate.*  

3. Будут проигнорированны все файлы по шаблону (ноль или более символов).tfstate.(ноль или более символов)  в всех папках и подпапках

crash.log

4.  Будут игнориироватся файл , файлы  crash.log

*.tfvars

5.  Будут проигнориированы все файлы по шаблону (ноль или более символов).tfvars во всех папках и подпапках

override.tf

6. Будут ингнорироватся файлы override.tf 

override.tf.json

7. Будут гнорироватся файлы  override.tf.json

*_override.tf

8. Будут игнорироватся файлы по шаблону (ноль или другое значение)_override.tf.json

*_override.tf.json

9. Будут игнорироваться файлы по шаблоны (ноль или другое значение)_override.tf.json

.terraformrc

10. Игнорирование файлов .terrafomrc


terraform.rc

11. Игнорированиие файлов terraform.rc
