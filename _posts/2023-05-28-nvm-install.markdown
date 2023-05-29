---
layout: post
title:  "Tutorial instalando nvm"
date:   2023-05-28 15:56:00 -0300
categories: Node_Js
---


Passo 1: Abra o terminal
Abra o terminal no seu sistema operacional. O processo pode variar dependendo do sistema operacional que você está usando:

- No macOS ou Linux: Abra o Terminal ou o aplicativo de linha de comando.
- No Windows: Abra o Prompt de Comando ou o PowerShell.

Passo 2: Baixe o script de instalação
Digite o seguinte comando no terminal para baixar o script de instalação do NVM:

```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash
```

O comando acima usa o `curl` para baixar o script de instalação diretamente do repositório oficial do NVM no GitHub.

Passo 3: Execute o script de instalação
Após o download do script, execute-o digitando o seguinte comando no terminal:

```
bash install.sh
```

Isso executará o script de instalação do NVM e instalará o NVM no seu sistema.

Passo 4: Configurar o NVM
Após a instalação, você precisará configurar o NVM no seu terminal. Para fazer isso, digite o seguinte comando no terminal:

```
source ~/.nvm/nvm.sh
```

Este comando carrega o arquivo `nvm.sh`, que configura o NVM no seu ambiente.

Passo 5: Verificar a instalação
Para verificar se a instalação foi bem-sucedida, digite o seguinte comando:

```
nvm --version
```

Isso exibirá a versão do NVM instalada no seu sistema, confirmando que a instalação foi concluída com êxito.

Passo 6: Instalar uma versão do Node.js
Agora que o NVM está instalado, você pode usar o comando `nvm` para instalar e gerenciar várias versões do Node.js no seu sistema. Para instalar a versão mais recente do Node.js, digite o seguinte comando:

```
nvm install node
```

Isso instalará a versão mais recente do Node.js no seu sistema. Você também pode instalar uma versão específica do Node.js usando o comando `nvm install <versão>`.

Passo 7: Verificar a instalação do Node.js
Para verificar se o Node.js foi instalado corretamente, digite o seguinte comando:

```
node --version
```

Isso exibirá a versão do Node.js instalada no seu sistema.

Agora você tem o NVM instalado e uma versão do Node.js configurada no seu sistema. Você pode usar o NVM para instalar e gerenciar facilmente diferentes versões do Node.js para seus projetos. Certifique-se de consultar a documentação oficial do NVM para obter mais informações sobre como usá-lo e explorar suas funcionalidades adicionais.

Espero que este tutorial tenha sido útil! Se você tiver alguma dúvida, fique à vontade para perguntar.