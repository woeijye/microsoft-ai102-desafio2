<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="40px" src="https://hermes.digitalinnovation.one/assets/diome/logo-minimized.png"></a>
    <span>Análisador de Documentos Anti-fraude com AzureAI</span>
</h1>

A solução, através de análise automatizada, avaliará se um cartão de crédito é válido ou não.

## Objetivo
Implementar uma solução de análise automatizada de documentos utilizando AzureAI para identificar padrões de fraude, validando a autenticidade e aumentando a segurança de transações e processos empresariais, visando garantir maior confiabilidade no processamento de documentos sensíveis.

## Ferramentas
[![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=30A3DC)](https://docs.github.com/)
[![Gmail](https://img.shields.io/badge/Gmail-333333?style=for-the-badge&logo=gmail&logoColor=red)](mailto:SEUGMAIL)
![Vscode](https://img.shields.io/badge/Vscode-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Azure](https://img.shields.io/badge/Azure-blue?style=for-the-badge&logo=microsoft%20azure&logoColor=blue&labelColor=FFFFFF&link=https%3A%2F%2Fimages.app.goo.gl%2FK7PN1jYJd57x4q7A8)
![Windows](https://img.shields.io/badge/Windows-000?style=for-the-badge&logo=windows&logoColor=2CA5E0)

## Percurso
<table>
  <thead>
    <tr align="left">
      <th>Nº</th>
      <th>Etapas</th>
      <th>Observações</th>
    </tr>
  </thead>
  <tbody align="left">
    <tr>
      <td>01</td>
      <td>Contas para acessos</td>
      <td>Gmail, Github e Azure</td>
    </tr>
    <tr>
      <td>02</td>
      <td>Criar Recurso e Implantar Serviços</td>
      <td>Portal Azure</td>
    </tr>
    <tr>
      <td>03</td>
      <td>Adicionar Contêiner para o Cartão de Crédito</td>
      <td>Azure AI Studio</td> 
    </tr>
    <tr>
      <td>04</td>
      <td>Criar a Camada de Front End</td>
      <td>VS Code</td> 
    </tr>
  </tbody>
  <tfoot></tfoot>
</table>

---
##  Pré-Requisitos

**CONTA DE E-MAIL**, para fazer acessos diversos 
- Para este projeto foi usado uma conta @gmail.
- A mesma foi usada para para acessar o github.
- A conta github usada para logar no portal.azure.com.

**CARTÃO DE CRÉDITO** válido 
- Será necessário no momento da criação da conta gratuita no Azure.

**CONTA AZURE**
- Criar a conta "gratuita".
- Usar o link fornecido no bootcamp: (https://aka.ms/oaiapply).
  

### Instruções

1. Criar **Grupo de recursos** dio-lab-doc-fraude no Portal Azure;

2. Implantar o serviço **Conta de Armazenamento**;

3. Implantar o serviço **Document Intelligence**;

4. Na guia Navegador de Armazenamento > Contêineres de blob > +Adicionar um contêiner > **cartoes**;

5. Na guia Visão Geral > Propriedades > Acesso anônimo ao blob > clicar em **Desabilitado**;

6. Em Permitir acesso anônimo ao Blob, clicar em **Habilitado**;

7. Ir para a guia Navegador de Armazenamento > Contêineres de blob > +Adicionar um contêiner > **cartoes**;

8. Clicar em **Alterar o nível de acesso** e aloterar o nível de acesso do contêiner 'cartoes' para **Blob(acesso de leitura anônimos somente para blobs)**;

9. Agora clicar em **Carregar** para testarmos se o cartão de crédito está sendo enviado para o document storage;

10. Acessar o Azure AI | Document Intelligenc Studio > Prebuilt models> **Credit Card**;
11.  Carregar a imagem do cartão de crédito a ser testado e clicar em **Run analysis**;
12.  Abrir o VSCODE;
13.  Codificar o arquivo .env;
14.  Codificar o arquivo Config.py;
15.  Codificar o arquivo app.py;
16.  Codificar o arquivo requirements.txt;
17.  Codificar o arquivo blob_service.py;
18.  Executar no terminal **run streamlit .\app.py** ;

---

## Instrutor
Henrique Eduardo Souza<br>
Microsoft MVP

##
<div align="center">Feito com carinho por <a href="https://github.com/woeijye">SON</a>.</div>
