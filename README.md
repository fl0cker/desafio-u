# desafio-u
Playbook Ansible que instala e configura um servidor Web com Wordpress

# Clone o repositório
```shell
git clone git@github.com:fl0cker/desafio-u.git
```
# Altere os arquivos abaixo informando o IP/DNS do alvo e a chave SSH

	inventory/hosts
		altere o caminho onde está a chave SSH (ansible_ssh_private_key_file)

# Execute o playbook informando na variável http_domain o domínio a ser configurado
```shell
ansible-playbook playbook.yml -e http_domain=example.com
```

  > **Pré-requisitos:** Ansible, Git, Chave SSH
