# ansible-categraf
Ansible playbook for Categraf

Note:
1）将categraf-v0.3.51-linux-amd64.tar.gz 安装文件放在ansible服务端机器的 /fun/soft 下

2）hosts文件 [categraf_machine] 下，填写需要安装categraf机器的ip地址

使用：

1）直接使用ansible命令行工具批量在一组主机上执行命令
ansible-playbook -i hosts -k install_categraf.yml
