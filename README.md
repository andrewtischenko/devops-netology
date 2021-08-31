# devops-netology
# Что будет игнорировано
# **/.terraform/*
# Игнорирование каталога и всех файлов в нем в корне проекта
#
# *.tfstate
# *.tfstate.*
# Игнорирование всех файлов с расширением tfstate
#
# crash.log
# Игнорирование файла crash.log в любом каталоге проекта
#
# *.tfvars
# Игнориование файлов с расширением tfvars в любом каталоге проекта
#
# override.tf
# override.tf.json
# *_override.tf
# *_override.tf.json
# Игнорирование файлов override.tf и override.tf.json во всем проекте, а так-же файлы в имени которых встречаются символы _override.tf и _override.tf.json
#
# .terraformrc
# terraform.rc
# Игнорирование файла terraform.rc во всем проекте и файлов с расширением terraformrc