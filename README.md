
**/.terraform/* -игнорировать все файлы и папки в катаоге .terraform, в коком бы месте каталог не находился.
*.tfstate -Игнорировать все файлы с расширением tfstate
*.tfvars -аналогично предыдущему (но со своим расширением)
.terraformrc -аналогично предыдущему (но со своим расширением)
*.tfstate.* -аналогично, только может быть другое расширение (вместо * может быть любое количество символов)
crash.log -игнорировать данный файл где бы он не находился.
override.tf -аналогично предыдущему
override.tf.json -аналогично предыдущему
terraform.rc -аналогично предыдущему
*_override.tf -игнорировать все файлы заканчивающиеся _override.tf
*_override.tf.json -игнорировать все файлы заканчивающиеся _override.tf.json
New test for lesson 3