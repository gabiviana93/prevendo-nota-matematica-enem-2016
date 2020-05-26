# Desafio Codenation - AceleraDev Data Science

O desafio consiste em criar um modelo para prever a nota da prova de matemática de quem participou do ENEM 2016 para participar do programa de aceleração.

## Prova do Enem 2016

O contexto do desafio gira em torno dos resultados do ENEM 2016 (disponíveis no arquivo train.csv). Este arquivo, e apenas ele, deve ser utilizado para todos os desafios. Qualquer dúvida a respeito das colunas, consulte o Dicionário dos Microdados do Enem 2016.

Muitas universidades brasileiras utilizam o ENEM para selecionar seus futuros alunos e alunas. Isto é feito com uma média ponderada das notas das provas de matemática, ciências da natureza, linguagens e códigos, ciências humanas e redação, com os pesos abaixo:

    matemática: 3
    ciências da natureza: 2
    linguagens e códigos: 1.5
    ciências humanas: 1
    redação: 3

No arquivo test.csv crie um modelo para prever nota da prova de matemática (coluna NU_NOTA_MT) de quem participou do ENEM 2016.

Salve sua resposta em um arquivo chamado answer.csv com duas colunas: NU_INSCRICAO e NU_NOTA_MT.

Faça o upload do arquivo answer.csv usando o botão “Submeter resposta”.

## Utilização

Para instalar as dependências, clone o projeto,acesse o diretório e use o código abaixo no terminal:

pip install -r requirements.txt