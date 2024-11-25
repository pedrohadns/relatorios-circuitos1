# Relatórios Acadêmicos em LaTeX

Este repositório contém o **modelo** para relatórios acadêmicos desenvolvido em LaTeX, além de servir como base para a criação de relatórios individuais em disciplinas do curso de **Engenharia de Computação** no **CEUNES - UFES, Campus São Mateus**.

## 🗂️ Organização do Repositório

1. **Branch Principal (`main`)**  
   Contém o modelo base do relatório, utilizado como referência para a criação de novos relatórios. Inclui:  
   - Arquivo `main.tex`: Estrutura e formatação padronizadas para relatórios.  
   - Arquivo `main.pdf`: Exemplo gerado a partir do modelo.  
   - Arquivos auxiliares (imagens, bibliografias, etc.) para personalização do modelo.  

2. **Forks para Relatórios**  
   Cada relatório individual deve ser criado como um *fork* deste repositório.  
   - O *fork* pode conter apenas os arquivos específicos do relatório.  
   - As modificações no modelo podem ser sincronizadas a partir da *main*, garantindo padronização.  

## ✏️ Modelo de Relatório

O modelo no branch principal segue um padrão técnico e acadêmico:  
- **Capa Personalizada**: Inclui informações da disciplina, curso, universidade e autor.  
- **Estrutura Interna**: Contém seções para introdução, desenvolvimento, resultados, e conclusões.

## 🚀 Como Utilizar o Modelo

1. Faça um *fork* deste repositório:  
   Clique no botão **Fork** no GitHub para criar sua cópia do repositório.  

2. Clone o *fork* para seu ambiente local:  
   ```bash
   git clone https://github.com/seu-usuario/nome-do-fork.git
   cd nome-do-fork
   ```

3. Edite o modelo para criar seu relatório:  
   Modifique o arquivo `main.tex` conforme necessário e adicione os conteúdos do relatório.  

4. Compile o arquivo para gerar o PDF:  
   ```bash
   pdflatex relatorio.tex
   biber relatorio
   pdflatex relatorio.tex
   pdflatex relatorio.tex
   ```

5. Sincronize com a branch principal, se necessário:  
   Para incorporar atualizações no modelo base:  
   ```bash
   git remote add upstream https://github.com/seu-usuario/relatorios-academicos.git
   git fetch upstream
   git merge upstream/main
   ```

6. Submeta seu relatório concluído ao GitHub.

## 🛠️ Tecnologias Utilizadas

- **LaTeX**: Para formatação e compilação dos relatórios.  
- **circuitikz**: Criação de circuitos elétricos com base no pacote TiKz.  
- **Biber**: Gerenciamento de referências bibliográficas.  

## 📖 Exemplos de Aplicação

- **Circuitos Elétricos 1**  
   Relatórios com tópicos como análise de circuitos resistivos, circuitos RC/LC, e filtros.  
- **Outras Disciplinas**  
   Modelos adaptáveis para disciplinas relacionadas a Engenharia de Computação e áreas afins.

## 🤝 Contribuições e Sugestões

Se desejar contribuir com melhorias no modelo:  
1. Faça um *fork* deste repositório.  
2. Crie uma nova *branch* para suas alterações:  
   ```bash
   git checkout -b minha-sugestao
   ```
3. Envie um *pull request* para revisão.
