# ansible
# 替换文件
# 变量文件files.yml
# 变量filename代表所要替换文件的名称
# 变量dirname代表替换文件所在的路径
# 执行前创建当天日期的目录，在该目录下创建files.yml文件，把想要替换的目标主机文件放到该目录下
# eg: ansible-playbook -i hosts change_files.yml -e "app_name=test date=20210706"
