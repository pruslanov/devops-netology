# devops-netology
First text line

# Игнорируем во всех поддректориях содержиое поддиретории .terraform
**/.terraform/*

# Игнорируем файл с расширением .tfstate и содержащие в названии .tfstate.
*.tfstate
*.tfstate.*

# Игноринуем логи Crash log files
crash.log
crash.*.log

# Exclude all .tfvars files, which are likely to contain sensitive data, such as
# password, private keys, and other secrets. These should not be part of version 
# control as they are data points which are potentially sensitive and subject 
# to change depending on the environment.
#
# Игнорируем файлы с оканчивающиеся на .tfvars и .tfvars.json
*.tfvars
*.tfvars.json

# Ignore override files as they are usually used to override resources locally and so
# are not checked in
# 
# Игнориуем файлы с именами override.tf и override.tf.json и окончивающиеся на _override.tf и _override.tf.json
override.tf
override.tf.json
*_override.tf
*_override.tf.json

# Включить example_override.tf после исключающего предыдущего правила 
#
# Include override files you do wish to add to version control using negated pattern
# !example_override.tf
# 

# Include tfplan files to ignore the plan output of command: terraform plan -out=tfplan
# example: *tfplan*

# Ignore CLI configuration files
# 
# Игнорировать файлы .terraformrc и terraform.rc
.terraformrc
terraform.rc
ADD ONE NEW LINE TO THE END
