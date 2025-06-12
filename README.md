# 🚀 Projeto DevOps - Deploy Automatizado com Vagrant + Ansible + Nginx

Este é um projeto hands-on desenvolvido durante o curso de DevOps da [Atlântico Avanti](https://www.atlanticoavanti.com.br/), com o objetivo de aplicar na prática o provisionamento automatizado de servidores utilizando **Vagrant** e **Ansible**. O resultado final é um servidor web configurado com **Nginx**, pronto para servir um site estático localmente.

---

## 🛠️ Tecnologias Utilizadas

- 🔧 Vagrant
- 📦 VirtualBox
- ⚙️ Ansible
- 🌐 Nginx
- 🐧 Ubuntu 20.04 (focal64)

---

## 📂 Estrutura do Projeto
```
├── Vagrantfile
├── playbook.yml
├── template/
│ ├── index.html
│ ├── style.css
│ └── img/
├── images/
│ ├── site.png
│ ├── playbook.png
│ └── vagrantfile.png
└── README.md
```
---

## ⚙️ Como Executar Localmente

### 1. Clone o repositório

```
git clone https://github.com/seuusuario/devops-hands-on.git
cd devops-hands-on
```
### 2. Inicie o ambiente com Vagrant

```
vagrant up
```
### 3. Acesse o site

```
http://localhost:8080
```
