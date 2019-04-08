# CURSO GIT E GITHUB - CODE EDUCATION

<strong>Este é meu primeiro projeto no github!</strong>

Após ter criado a conta e adicionado a SSH key, no terminal da minha máquina, entrei na pasta do meu projeto e executei os seguintes comandos:

<ul>
  <li><strong>git remote add origin https://github.com/gufodev/git-test</strong>: adiciona o projeto ao repositório</li>
  <li><strong>git push origin master</strong>: sobe o projeto para o repositório</li>
</ul>

Logo após, realizei algumas alterações no meu projeto:

<ul>
  <li><strong>git add nome-arquivo</strong>: prepara o arquivo para ser comitado (1º estágio)</li>
  <li><strong>git commit -m 'texto'</strong>: comita o(s) arquivo(s) (2º estágio)</li>
</ul>

Em seguida atualizei o projeto no repositório:

<ul>
  <li><strong>git pull origin nome-branch</strong> ou <strong>git pull</strong>: Atualiza um único branch ou TODOS os branchs</li>
</ul>

Para gerar um novo Release utilizei os seguintes comandos

<ul>
  <li><strong>git tag -l</strong>: lista o ultimo release lançado</li>
  <li><strong>git tag 1.0.1</strong>: adiciona uma correção (patch)</li>
  <li><strong>git push origin master --tags</strong>: sobe a tag gerada e gera um novo release</li>
</ul>