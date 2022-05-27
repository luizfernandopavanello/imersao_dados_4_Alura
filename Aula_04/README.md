<div align="center">
    <img src="https://www.alura.com.br/assets/img/imersoes/imersao-dados-3ed/logo-imersao-dados.1647533644.svg" />
    <br/>
    <img 
src="https://www.alura.com.br/assets/img/home/alura-logo.1647533643.svg" alt="Alura" />
</div>

### Aula 4 - Missão Impossivel: Cruzando bases de Dados
## Participe e vá mais fundo

Boas-vindas à quarta aula da Imersão Dados 4ª Edição!

Chegamos a famosa quarta aula da Imersão, apelidada carinhosamente pelo Paulo Silveira como Missão Impossível. Mas não se preocupe! Ela é mais complexa que as outras aulas, entretanto não há o que temer. No notebook da aula está todo passo a passo. Você pode primeiro acompanhar o vídeo e depois reproduzir o código.

Na nossa base de dados temos algumas poucas informações sobre o imóvel. Uma opção que temos é vincular e enriquecer os nossos dados com informações extras. É exatamente isso que faremos hoje: vamos cruzar os dados que temos com dados do IBGE.

Para executar essa tarefa vamos trabalhar com dados de geolocalização, CEPs, conceitos geometria computacional e muito mais.

<h4>Para ver os exercícios e todo o conteúdo que foi dado em aula, siga os passos abaixo</h4>

<ul>
<li>Acesse o notebook da <a href="https://colab.research.google.com/drive/1WzaYKTJuVoQ1_WeVdBwKsmkCV9PU7IGD?usp=sharing">aula 04.</a> com todo o código trabalhado em aula.</li>
<li>Se você está cheio de dúvidas de como realizamos os cruzamentos entre as bases de dados, esse <a href="https://medium.com/creditas-tech/incrementando-dados-geogr%C3%A1ficos-com-o-censo-nacional-do-ibge-54d342c4bdcf">artigo da Creditas</a> pode te ajudar!</li>
<li>Nesta aula vamos precisar da base de dados de endereços. Baixe <a href="https://drive.google.com/file/d/1u2qPFtYaE4of3Vb3d7yQEVEbS5FdQ_FP/view?usp=sharing">neste link</a> e salvar no seu drive.</li>
<li>Também precisaremos dos dados dos <a href="https://drive.google.com/drive/folders/1CycoanzYN2oxKHPO6zxvIQ6Og1LBcujv?usp=sharing">setores censitários</a>. Não esqueça que você precisa dos 4 arquivos na mesma pasta para leitura.</li>
<li>Se você não reproduziu o código sozinho, não se preocupe! Aqui você acessa a <a href="https://drive.google.com/file/d/1KyaCnwYt3vVV_7O0VktZorRhsMWD9hQQ/view?usp=sharing">base dados_geo</a> e aqui a <a href="https://drive.google.com/file/d/1iAFJhgMUquxsbGxM1pWz9BLjpC9SULKr/view?usp=sharing">base dados_vendas_censo</a></li>
<li>Na parte superior esquerdo, clique em >File, logo depois em >Save a copy in Drive.</li>
<li>Se você não estiver logado em uma conta Gmail, um pop-up solicitará que você crie ou faça login em uma conta Google.</li>
<li>Feito o login, uma cópia da aula é criada em seu Drive (pasta Colab Notebook, criada automaticamente).</li>
<li>Abra o notebook e boa diversão!</li>
</ul>

<h4>Desafios desta aula</h4>
<ul>    
    <li>Realizar uma análise dos dados do IBGE por mapa, analisando a distribuição de renda.</li>
    <li>Repassar a aula para entender melhor o que foi realizado.</li>
    <li>Aprofundar a análise entre dados de vendas e renda.</li>
    <li>Realizar a análise exploratória e encontrar variáveis relevantes para solução do problema</li>        
</ul>
    
<h4>Alguns lembretes e dicas</h4>

<ul>
    <li>Que tal aprender mais sobre Geopandas com este <a href="https://medium.com/creditas-tech/dados-georreferenciados-explora%C3%A7%C3%A3o-e-visualiza%C3%A7%C3%A3o-com-python-edd51e7c53da">artigo da Creditas!</a></li>
    <li>Podemos usar dados do IBGE para criar novas features, de uma maneira diferente que fizemos em aula. Se liga <a href="https://medium.com/creditas-tech/criando-features-de-machine-learning-a-partir-de-nomes-de-cidades-7149fae7778e">neste artigo!</a></li>
    <li>Quer entender mais sobre Boxplot? <a href="https://www.alura.com.br/artigos/melhorando-a-analise-com-o-boxplot">acesse este artigo da Alura.</a></li>
    <li>Para baixar os dados do IBGE você pode acessar este <a href="https://gist.githubusercontent.com/tgcsantos/85f8c7b0a2edbc3e27fcad619b37d886/raw/a4954781e6bca9cb804062a3eea0b3b84679daf4/Basico_SP1.csv">link.</a></li>
    <li>Para acessar o dicionário de dados do IBGE que estamos trabalhando, é só <a href="https://drive.google.com/file/d/1WVTqfKtHOOk5X1AWaSOn6NLaO7cix2m4/view?usp=sharing">clicar aqui.</a></li>
    <li>Que tal explorar mais sobre <a href="https://geopandas.org/en/stable/">GeoPandas</a></li>
    <li>Quer conhecer um pouco mais sobre String? Se liga <a href="https://panda.ime.usp.br/pensepy/static/pensepy/08-Strings/strings.html">neste material.</a></li>
    <li>Um guia rápido para o <a href="https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf">Pandas.</a></li>
</ul>

<br/>
<div align="center">
<h5 align="center">Bons estudos e até a próxima aula!</h5>

<blockquote align="center">“Faça seu melhor, mas sempre com prazo de entrega!”</blockquote>

<div align="center">
<img width="100" src="https://www.alura.com.br/assets/img/imersoes/imersao-dados/logo-mersao.1647533644.svg" />
</div>

<div/>
