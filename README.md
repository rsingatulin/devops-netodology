# devops-netology
Благодаря .gitignore при коммите будут проигнорированы все файлы, подпадающие под действие шаблонов
**/.terraform/* -  все файлы в папке .terraform, где бы она не находилась
*.tfstate  - файлы с расширением tfstate
*.tfstate.*  - файлы с расширением  *.tfstate, *.tfstate.*

crash.log - файл crash.log
crash.*.log - файлы crash.любое количество любых символов.log

*.tfvars - файлы с расширением tfvars
*.tfvars.json - файлы заканчивающиеся на tfvars.json

override.tf - файл override.tf
override.tf.json - файл - override.tf.json 
*_override.tf - файл с любым началом и _override.tf
*_override.tf.json - файл с любым началом и _override.tf.json

.terraformrc - файл .terraformrc
terraform.rc - файл terraform.rc
new line for branch fix

Change by PyCharm Git Window
Commit by PyCharm 