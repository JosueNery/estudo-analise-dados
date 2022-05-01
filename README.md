# Análise de Dados

Este repositório tem como objetivo apresentar algumas atividades produzidas na disciplina Análise de Dados e IA.

*Os arquivos em pdf possuem as análises dos dados apresentados.*

## Brasileirão Série A
  *Objetivo* : Obter estimativas pontuais e por intervalos de 95% de confiança. Obter os dados dos times que disputaram a série A do campeonato Brasileiro de 2003 a 2020. 
  >Dados de interesse: pontuação final, número de gols marcados, número de gols sofridos
  
  Para os dados dos quilômetros percorridos por cada time, foi utilizado a api do google maps que recebia a cidade de destino e de partida para retornar a distância.
  As tabelas das relações dos jogos de cada time em cada ano foi encontrada manualmente, porém foi desenvolvido um programa em python para utilizar a api do google,     recebendo os dados em um arquivo .csv, formatando alguns detalhes e retornando o arquivo .csv com uma nova coluna de "km".   
  >
  ><a href="https://colab.research.google.com/drive/1z78Jr882qr1cLGaN0b1vwfCkct3g5ObB?usp=sharing"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
      
    
  Os dados foram estruturados da seguinte forma em .csv:
  
  ![Capturar32](https://user-images.githubusercontent.com/62897903/166124556-92f17c25-0e6f-433a-9fcf-7886f1cd9752.PNG)

  <a href="https://docs.google.com/spreadsheets/d/1HnYOlqWdgVpCDBqVorIxc9IofYTrrXIJY4VaaekV540/edit?usp=sharing" target="_blank"> Link para o arquivo completo no Planilhas Google </a>
  
## Análise BI-RADS

 Analisar os dados de massas mamográficas de classificação em maligno ou benigno com base nos atributos BI-RADS e na idade da paciente. O BI-RADS se refere a Breast Imaging Reporting and Data System (Sistema de Relatório de Dados sobre Imagem da Mama), que estima qual a chance de determinada imagem da mamografia ser câncer. Variando de 0 a 6, o BI-RADS ajuda a orientar a conduta médica.
