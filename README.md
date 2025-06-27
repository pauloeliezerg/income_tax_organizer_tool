# Control App

Uma planilha de controle financeiro em Google Sheets para coleta e organização de dados pessoais, informes bancários e lançamentos de receitas.

---

## 📋 Sumário

- [Visão Geral](#visão-geral)  
- [Funcionalidades](#funcionalidades)  
- [Como Usar](#como-usar)  
- [Configurações e Permissões](#configurações-e-permissões)  
- [Personalização](#personalização)  
- [Contribuindo](#contribuindo)  
- [Licença](#licença)  

---

## 🔍 Visão Geral

O **Control App** é uma planilha interativa construída no Google Sheets para:

1. **Cadastro de dados pessoais** (Titular e Cônjuge)  
2. **Levantamento de rendimentos bancários** com upload de comprovantes  
3. **Lançamentos mês a mês de receitas** a partir de notas/extratos  

Tudo isso com validação de dados, menus suspensos e fórmulas de consolidação automática.

---

## ⚙️ Funcionalidades

- **Guia “Titular”**  
  - Cadastro de informações pessoais (nome, CPF, endereço, contato, etc.)  
  - Flags para alterações em entregas anteriores e residência no exterior  

- **Guia “Informes”**  
  - Registro de até 3 bancos por cliente  
  - Cálculo automático do total de rendimentos  
  - Upload de PDFs de informes  

- **Guia “Notas”**  
  - Lançamento mensal de entradas (data, categoria, valor)  
  - Listas suspensas de categorias pré-definidas  
  - Agregação de valores por mês  

- Proteção de abas e bloqueio de células, deixando apenas as células de entrada desbloqueadas.  
- Layout responsivo e formatação condicional para facilitar a navegação e leitura.

---

## 🚀 Como Usar

1. **Faça uma cópia** da planilha modelo:  
   - Abra o Google Sheets do projeto.  
   - `Arquivo` → `Fazer uma cópia`.  
2. **Preencha** a aba **Titular** com seus dados pessoais.  
3. Na aba **Informes**, selecione o banco, insira os valores e faça upload dos PDFs na coluna “Anexo”.  
4. Em **Notas**, escolha data, categoria e informe o valor de cada entrada.  
5. Confira o total de rendimentos e a consolidação automática dos valores.

---

## 🔧 Configurações e Permissões

- As abas estão protegidas; apenas as células amarelas estão desbloqueadas para edição.  
- Caso utilize scripts (Google Apps Script), conceda as permissões solicitadas ao executar pela primeira vez:
  - Acesso e gerenciamento da planilha no Google Sheets.  
  - Leitura e escrita de arquivos no Google Drive (para anexos).

---

## 🎨 Personalização

- **Cores e Formatação:** ajuste via `Formatar` → `Regras de formatação condicional`.  
- **Listas Suspensas:** edite os intervalos de validação de dados conforme suas categorias.  
- **Automação:** modifique ou acrescente trechos no arquivo de script (se houver) para funcionalidades extras (e-mail, geração de relatórios, exportação em PDF etc.).
