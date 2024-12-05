# Modulo_GitEbac  
Tudo que aprendi no módulo de Git da profissão de engenheiro front-end na EBAC.

---

```bash
# Controle de Versão com Git e GitHub

## Configuração Inicial
git config --global user.name "Seu Nome"         # Configurar o nome do usuário
git config --global user.email "Seu E-mail"     # Configurar o e-mail do usuário

## Criar Repositório
git init                                        # Inicializar um repositório local

## Adicionar Arquivos ao Stage
git add nome_do_arquivo                         # Adicionar um arquivo específico
git add .                                       # Adicionar todos os arquivos no diretório

## Remover Arquivo do Stage
git rm --cached nome_do_arquivo                 # Remover um arquivo do estado de stage

## Salvar Alterações (Commit)
git commit -m "Sua mensagem descritiva"         # Criar um commit com mensagem descritiva

## Padrões para Mensagens de Commit
git commit -m "chore: ajustando estilos"        # Pequenas tarefas
git commit -m "fix: corrigindo erro de cálculo" # Correções de bugs
git commit -m "feat: adicionando funcionalidade" # Novas funcionalidades
git commit -m "docs: atualizando README.md"     # Atualizações de documentação

## Histórico de Commits
git log                                         # Histórico completo
git log -n 2 --oneline                          # Resumo dos últimos 2 commits
git log --stat                                  # Exibir alterações detalhadas

## Branching e Controle de Ramificações
git branch                                      # Listar branches
git branch nova_branch                          # Criar uma nova branch
git checkout nome_branch                        # Trocar para uma branch existente
git checkout -b nova_branch                     # Criar e mudar para a nova branch
git branch -D nome_branch                       # Deletar uma branch

## Mesclar Branches
git merge nome_branch                           # Mesclar outra branch na atual

## Resolver Conflitos
git add nome_do_arquivo                         # Marcar conflito resolvido
git commit -m "Resolvendo conflito"             # Criar commit após resolver o conflito

## Trabalhando com GitHub

# Clonar um Repositório
git clone LINK                                  # Clonar repositório do GitHub
git clone LINK -l pasta_destino                 # Clonar em uma pasta específica

# Enviar e Receber Atualizações
git push                                        # Enviar alterações para o GitHub
git pull                                        # Receber atualizações do repositório remoto
git push origin nome_da_branch                  # Enviar alterações de uma branch específica
