# python-cloud-trabalho
Repositório para trabalho de Python na nuvem

Trabalho: Python + Cloud + GitHub
Disciplina: Cloud Computing - 2º período ADS/CC

n Objetivos
1. Consolidar o aprendizado de Python com APIs, JSON e Flask. 
2. Compreender a relação entre Python e Cloud Computing.
3. Praticar versionamento com Git e GitHub (commit, push, pull). 
4. Desenvolver autonomia na documentação de projetos.

n Tarefas
1. Criar repositório público no GitHub chamado 'python-cloud-trabalho'. 

	https://github.com/kleber-lim/python-cloud-trabalho

2. Adicionar README.md explicando o projeto.



3. Scripts obrigatórios:
   - API GitHub (mostrar nome, descrição e estrelas).
   - API Clima (mostrar temperatura e vento de Curitiba + outra cidade). 
   - JSON Local (salvar e ler dados de alunos).
   - API Flask (rotas /, /alunos, /saudacao/<nome>, /curso/<curso>).
4. Fazer commits separados para cada script.
5. Enviar alterações ao GitHub (push).
6. Testar git pull/clonar em outra máquina.
7. Documentar tudo no README.md com prints de execução.


Git Cheat Sheet – Guia Rápido
Configuração inicial
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@example.com"

Fluxo de Trabalho Básico
git init                      # Inicia repositório local
git status                    # Verifica status
git add .                     # Adiciona todos os arquivos 
git commit -m "mensagem"      # Salva versão
git remote add origin URL     # Conecta ao GitHub 
git push -u origin main       # Envia primeira vez
git push                      # Envia alterações
git pull                      # Atualiza do GitHub
git clone URL                 # Clona repositório existente 
git log --oneline             # Histórico resumido

n Observação Final
Sempre usar mensagens de commit claras e descritivas. 
Exemplo: git commit -m "Adicionei rota /curso no Flask".
