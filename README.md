# linux-projeto1-iac
# README

## Script de Criação de Estrutura de Diretórios e Usuários

Este repositório contém um script em Bash que automatiza a criação de diretórios, grupos e usuários em um sistema Linux. O objetivo é preparar um ambiente de trabalho organizado e seguro, com permissões específicas para cada grupo.

### Descrição do Script

O script realiza as seguintes operações:

1. **Criação de Diretórios**: 
   - Cria os diretórios `/publico`, `/adm`, `/ven`, e `/sec`.
  
2. **Criação de Grupos de Usuários**:
   - Verifica se os grupos `GRP_ADM`, `GRP_VEN`, e `GRP_SEC` já existem. Se existirem, eles são excluídos e recriados.

3. **Criação de Usuários**:
   - Cria um conjunto de usuários para cada grupo, com senhas pré-definidas. Os usuários são:
     - **Grupo ADM**: `carlos`, `maria`, `joao`
     - **Grupo VEN**: `debora`, `sebastiana`, `roberto`
     - **Grupo SEC**: `josefina`, `amanda`, `rogerio`

4. **Definição de Permissões**:
   - Define as permissões dos diretórios:
     - `/adm`, `/ven`, `/sec`: Permissões 770 (somente o proprietário e o grupo têm acesso total).
     - `/publico`: Permissão 777 (todos têm acesso total).

### Como Executar o Script

1. **Clone o Repositório**:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   
   cd seu-repositorio
Dê Permissão de Execução ao Script:

bash
Copiar código
chmod +x seu-script.sh
Execute o Script como Root:

bash
Copiar código
sudo ./seu-script.sh
Dependências
O script foi escrito para ser executado em sistemas Linux que suportam Bash.
O comando openssl deve estar instalado para a criação de senhas.
Considerações de Segurança
As senhas dos usuários estão definidas no script. Para ambientes de produção, considere métodos mais seguros para gerenciar senhas.
Certifique-se de que o script seja executado em um ambiente seguro e controlado.
Contribuições
Sinta-se à vontade para contribuir com melhorias ou novas funcionalidades. Sinta-se livre para abrir uma issue ou fazer um pull request!

Licença
Este projeto está licenciado sob a MIT License.

Contato
Para mais informações, você pode entrar em contato pelo e-mail: seu-email@exemplo.com.

javascript
Copiar código

Você pode substituir os placeholders (como `seu-usuario`, `seu-repositorio`, e `rafael.guedes1020@gmail.com`) com as informações relevantes do seu projeto. Se precisar de mais alguma coisa, é só avisar!



