# <img src="https://github.com/user-attachments/assets/caabfdf0-0f9e-44a3-8200-c6579fe87887" alt="Ícone de descrição" width="28"> Descrição
Um site que exibe tarefas pendentes e concluídas.

# <sub><img src="https://img.icons8.com/?size=100&id=L3V7IDcwKTn2&format=png&color=000000" alt="Ícone de tarefa" width="34"></sub> Página
![image](https://github.com/user-attachments/assets/de891fa4-a392-4fff-81cb-6f3f9ed354b2)

# <img src="https://img.icons8.com/?size=100&id=33039&format=png&color=000000" alt="Ícone da AWS" width="34"> Configuração do AWS
### Instalação do Apache, do PHP e inicialização do serviço
```
sudo yum update -y
```
```
sudo yum install -y httpd php
```
```
sudo systemctl enable httpd
```
```
sudo chown -R ec2-user:apache /var/www/html
```
```
sudo chmod -R 755 /var/www/html
```

# <img src="https://img.icons8.com/?size=100&id=duiaqXXFFuge&format=png&color=000000" alt="Ícone do PuTTy" width="32"> Transferência dos arquivos via PuTTy
### Arquivo de Tarefas
```
sudo nano /var/www/html/tarefas.php
```
### Index
```
sudo nano /var/www/html/index.php
```
### Arquivo de estilo
```
sudo mkdir /var/www/html/css
```
```
sudo nano /var/www/html/css/style.css
```
