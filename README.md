# 📘 ChatIF-doc

Repositório oficial da documentação do Trabalho de Conclusão de Curso (TCC) intitulado **“ChatIF”**.

Este trabalho foi desenvolvido como requisito para a obtenção do título de **Especialista em Desenvolvimento WEB** pelo Instituto Federal de Educação, Ciência e Tecnologia de São Paulo (IFSP), Câmpus Itapetininga.

O repositório é destinado ao versionamento e organização da **monografia desenvolvida em LaTeX**, contendo todos os arquivos necessários para compilação do documento final.

---

## 🎓 Sobre o Projeto

O **ChatIF** é um sistema de Chatbot com Inteligência Artificial desenvolvido com foco em aplicações educacionais.

A proposta do trabalho envolve:

- Aplicação de conceitos de Inteligência Artificial
- Utilização de Large Language Models (LLMs)
- Integração entre frontend e backend
- Gerenciamento de contexto conversacional
- Persistência de dados
- Documentação acadêmica estruturada em LaTeX

Este repositório contém exclusivamente a **documentação acadêmica (monografia)**.  
O código-fonte do sistema pode estar disponível em repositório separado.

---

## 🛠 Tecnologias Utilizadas no Projeto

Embora este repositório seja voltado à documentação, o sistema ChatIF foi desenvolvido com as seguintes tecnologias:

- **Frontend:** Vue.js  
- **Backend:** Python  
- **Banco de Dados:** Redis  
- **Documentação (Monografia):** LaTeX  

---

## 📂 Estrutura do Repositório

A estrutura pode variar conforme organização interna, mas geralmente inclui:

```
ChatIF-doc/
│
├── utfpr-tcc.tex          # Arquivo principal do documento
├── capitulos/             # Capítulos do trabalho
├── pre-textuais/          # Elementos pré-textuais
├── pos-textuais/          # Elementos pós-textuais
├── imagens/               # Figuras e diagramas
├── referencias.bib        # Base bibliográfica
└── utfpr-tcc.pdf          # Documento final compilado
```

---

## ▶️ Compilação do Documento

### 📄 Visualização

Para visualizar o documento final, basta abrir o arquivo:

```
utfpr-tcc.pdf
```

### ⚙️ Compilação Manual

Caso deseje compilar o documento-fonte em LaTeX, será necessário ter uma distribuição instalada, como:

- MiKTeX  
- TeX Live  

Execute os seguintes comandos no terminal:

```bash
pdflatex utfpr-tcc.tex
bibtex utfpr-tcc.aux
pdflatex utfpr-tcc.tex
pdflatex utfpr-tcc.tex
```

Esses comandos garantem:

- Processamento correto das referências bibliográficas  
- Atualização do sumário  
- Correção de citações cruzadas  
- Numeração adequada de figuras e tabelas  

---

## 📌 Objetivo do Repositório

- Manter o versionamento do documento acadêmico  
- Registrar a evolução do trabalho  
- Garantir organização e backup do TCC  
- Servir como referência para estudos futuros  

---

## 🤝 Contribuição

Este repositório é destinado principalmente para fins de documentação acadêmica.

Caso tenha interesse em colaborar no desenvolvimento do aplicativo ou discutir o projeto, sinta-se à vontade para:

- Abrir uma *issue*
- Entrar em contato com o autor

---

## 👨‍🎓 Autor

**Eduardo Santos de Almeida**

Especialista em Computação Aplicada à Educação  
Graduado em Análise e Desenvolvimento de Sistemas  

---

## 📄 Licença

Este projeto possui finalidade acadêmica.

O conteúdo pode ser utilizado como referência para fins de estudo, respeitando as normas institucionais e as boas práticas de citação acadêmica.
