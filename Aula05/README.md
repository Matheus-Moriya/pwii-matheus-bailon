## Criação de um projeto Laravel

 **1º Passo:** Instale o PHP e o Composer executando o comando abaixo

**Windows PowerShell (Execute como administrador):**
``` Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://php.new/install/windows/8.4'))```

**Linux:**
```/bin/bash -c "$(curl -fsSL https://php.new/install/linux/8.4)"```

**MacOS:**
```/bin/bash -c "$(curl -fsSL https://php.new/install/mac/8.4)"```

**2º Passo:** Abra a pasta em que o projeto será criado e execute o comando abaixo:
```Laravel new novo-projeto```

**3º Passo:** escolha os kits que serão usados no projetos escrevendo os nomes

**4º Passo:** abra a pasta usando o comando abaixo:
```cd novo-projeto```

e depois rode o composer:
```composer run dev```

**5º Passo:** Abra o porjeto clicando no link segurando a tecla CTRL 

## Configuração do projeto Laravel

**1ºPasso:** Abra o Windows PowerShell como administrador e execute o comando abaixo:
```Set-ExecutionPolicy RemoteSigned```
E responda a pergunta do comando com "Y"

**2º Passo:** Abra o projeto no Visual Studio Code, copie o arquivo ".env.example" e o renomeie para ".env"

**3º Passo:** Abra o projeto no PowerShell e execute os comandos abaixo para instalar o composer e o npm:

1:
```composer install```

2:
```npm install```

3:
`` npm run build`` 

**4º Passo:** Crie uma chave para o projeto executando o comando abaixo no PowerShell:
```php artisan key:generate```

Depois execute o comando abaixo e responda a pergunta com "yes"
```php artisan migrate```

**5º Passo:** Abra o link do projeto ao lado da frase "INFO Server running  on-" segurando a tecla CRTL 
