# Phishing para captura de senhas
## Durante o phishing tambem é possivel encontrar:
IP, IP Type, User Os, User agent, version 32bits or 64bits, browser, location
Geolocation(lat, lon), Currency

## Porque foi utilizado o PyPhisher:
##### Because it is phishing tool in python. Includes popular websites like facebook, twitter, instagram, github, reddit, gmail and many others.


### Ferramentas
- Kali Linux
- PyPhisher

### Configurando o Phishing no Kali Linux

- Iniciando: ``` PyPhisher ```
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ``` Site Cloner ```
- URL para clone: http://www.facebook.com

# Como instalar e utilizar:
##### Install dependencies (git, python, php ssh)

 - For Debian (Ubuntu, Kali-Linux, Parrot)
    - ```sudo apt install git python3 python3-pip php openssh-client -y```
 - For Arch (Manjaro)
    - ```sudo pacman -S git python3 python-pip php openssh --noconfirm```
 - For Redhat(Fedora)
    - ```sudo dnf install git python3 php openssh -y```
 - For Termux
    - ```pkg install git python3 python-pip php openssh -y```

##### Clone this repository

 - ```git clone https://github.com/KasRoudra/PyPhisher```

##### Enter the directory
 - ```cd PyPhisher```

##### Install all modules
 - ```pip3 install -r files/requirements.txt --break-system-packages```

##### Run the tool
 - ```python3 pyphisher.py```

#### Or, directly run
```
wget https://raw.githubusercontent.com/KasRoudra/PyPhisher/main/pyphisher.py && python3 pyphisher.py

```

### Pip
 - `pip3 install pyphisher` [For Termux]
 - `sudo pip3 install pyphisher  --break-system-packages` [For Linux]
 - `pyphisher`

### Docker

 - `sudo docker pull kasroudra/pyphisher`
 - `sudo docker run --rm -it kasroudra/pyphisher`


### Resutados

### Nessa imagem já pode ser exibida a senha digitada durante o teste
![Alt text](image-1.png)

### Aqui já podemos visualizar os Dados coletados através do IP
![Alt text](image.png)

Esses dados de IP normalmente são coletados após 1/2 minutos da entrada do usuario.

#### video de demonstração
https://www.youtube.com/watch?v=xIEuJkmJ8F0
