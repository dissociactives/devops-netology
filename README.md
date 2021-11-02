# devops-netology

# Все файлы из папки .terraform, находящейся в любом из каталогов репозитория.
**/.terraform/*

# Все файлы в корне репозитория по двум маскам.
*.tfstate
*.tfstate.*

# Файл crash.log в корне репозитория.
crash.log

# Все файлы в корне репозитория, имя которых оканчивается на .tfvars
*.tfvars

# Ignore override files as they are usually used to override resources locally and so
# are not checked in
# Файлы в корне репозитория override.tf, override.tf.json и файлы, имя которых оканчивается на _override.tf и _override.tf.json. 
override.tf
override.tf.json
*_override.tf
*_override.tf.json

# Файлы в корне репозитория .terraformrc & terraform.rc
.terraformrc
terraform.rc