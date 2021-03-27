# desafio-u
Playbook Ansible que instala e configura um servidor Web com Wordpress

# Clonando o repositório
```shell
git clone git@github.com:fl0cker/desafio-u.git
```
# Altere os arquivos abaixo

	inventory/hosts
		altere o local onde está a chave na sua maquina (ansible_ssh_private_key_file)

# Execute o playbook
```shell
ansible-playbook playbook.yml
```

  > **Pré-requisitos:** Ansible, Git, Chave SSH
