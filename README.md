# Scraper_FII
<h3>Web scraping para seleção de Fundos de Investimentos Imobiliários</h3>

Python Notebook para localização de opções de baixo valor, apelidados de pozinhos.

Projeto Python Notebook utilizando as bibliotecas "requests", "beautifulsoup4", "statistics" e "pandas".<br>
Neste repositório existem dois algoritmos que realizam a filtragem e seleção dos FII que pagam rendimentos mensais acima da inflação (IPCA 12 meses). <br>
O arquivo chamado "FII" retorna uma lista (carteira compilada) de papeis que passaram pelo filtro de pagamentos de rendimentos acima do IPCA 12 meses, além trazes apenas os papeis com maior liquidez no mercado e a relação Preço pelo Valor Patrimonial (P/VP). <br>
O outro arquivo, "FII_Segmentado", tem o mesmo princípio, mas descarta o filtro da relação P/VP e traz apenas um papel de cada segmento de atuação do Fundo (seja títulos, hosital, residencial, lajes corporativas, etc) que melhor paga rendimentos. Segmentar a carteira, pulverizando os investimentos em diferentes setores é o recomendado para não ficar muito exposto a oscilações fortes no valor total dos ativos. <br>
<br>
DISCLAIMER: Não sou especialista em investimentos e não recomendo que você se arrisque no mundo da renda variável sem uma boa base de conhecimento. Procure recomendações de especialistas e leituras para lhe dar segurança e saber o que está fazendo.

<a href="https://colab.research.google.com/drive/1qM3dUbjXVuHq5-a2WGHPrFL7n3d09knT?usp=sharing">FII no Google Colab</a><br>
<a href="https://colab.research.google.com/drive/1mCY6XTq-aY-bIX4DKNh0k0ESEWQKcqJ0?usp=sharing">FII_Segmentado no Google Colab</a>
