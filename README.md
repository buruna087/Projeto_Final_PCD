<img width="1300" height="252" alt="image" src="https://github.com/user-attachments/assets/433844c6-c5d0-4890-bc05-837aad7c6ea1" />


<div align="center">

# <h1 align="center"> Gráficos da curva de titulação ácido-base
</div>

## Índice
<!--ts-->
* [Descrição do Projeto](##Descrição-do-Projeto)
* [Conteúdo do repositório](##Conteúdo-do-repositório)
* [Bibliotecas utilizadas](##Bibliotecas-utilizadas)
* [Como funciona?](##Como-funciona-?)
* [Gráficos gerados](##Gráficos-gerados)
* [Conclusão](##Conclusão)
* [Referências](##Referências)
* [Desenvolvedora do projeto](##Desenvolvedora-do-Projeto)
* [Professores](##Professores)
* [Agradecimentos](##Agradecimentos)
<!--te-->

## Descrição do Projeto 
<p align="justify"> O projeto apresentado foi desenvolvido como parte da avaliação dos conhecimentos adquiridos no decorrer do 1º semestre letivo de 2026 na disciplina de Prátca em Ciência de Dados. Essa disciplina foi ministrada pelos docentes Prof. Dr. Daniel Roberto Cassar, Prof. Dr. James Moraes de Almeida e Prof. Dr. Leandro Nascimento Lemos. Neste projeto foi desenvolvida uma ferramenta em linguagem Python que gera gráficos referentes a curva de titulação de uma solução ácida fraca monoprotonada ou básica fraca monohidroxilada. O usuário fonece os dados solicitados e, a partir disso, os gráficos são gerados e salvos em formato png para que seja possível a visualização do comportamento da solução durante a titulação. Com essa proposta, é esperado que os usuários possam ter uma ferramenta que os ajude a visualizar o processo de titulação contendo somente os parâmetros da reação que precisa ser avaliada. A ferramenta foi pensada como uma forma de ajudar não somente estudantes que estão iniciando suas vidas em laboratórios e precisam de gráficos para estudar o comportamento da titulação, como também aqueles que buscam aprofundar seus conhecimentos no assunto sem a necessidade realizar experimentos físicos. 

## Conteúdo do repositório
<p align="justify"> Este repositório contém todos os códigos utilizados - presentes no notebook Jupyter, que apresenta a explicação detalhada de cada célula do código - bem como exemplos de como a ferramenta apresentada conseguiu gerar gráficos (presente no README)

## Bibliotecas utilizadas
- Numpy - utilizada para gerar as curvas de titulação e calcular logaritmos;

- matplotlib.pyplot - utilizada geração dos gráficos da curva de titulação.

## Como funciona? 
<p align="justify"> A ferramenta possui dois modos nos quais os gráficos pode ser gerados: o modo 1 e o modo 2. O modo 1 diz respeito a titulação entre um ácido fraco com uma base forte, enquanto o modo 2 funciona de maneira contrária, com a titulação de uma base fraca com um ácido forte. O usuário deve fornecer as concentrações da solução titulada e da solução que vai adicionada, bem como o volume da solução que vai ser titulada e o pKa ou pKb (a depender do modo escolhido). Além disso, o usuário tem a liberdade de escolher a unidade de medida (mililitro ou litro) que o volume vai ser adicionado. A partir desses dados, as funções auxilires criadas serão executadas para que o gráfico seja plotado, possibilitanto a visualização do usuário. Um adendo importante é que as condições definidas para o bom funcionamento e aproveitamento da ferramenta pelo usuário são exibidas antes do começo das perguntas para gerar o gráfico, sendo especificado quais condições devem ser seguida e quais erros devem ser evitados ao submeter os dados. O descumprimento dessas normas pode ocasionar em erros na geração do gráfico ou acarretar em gráficos que não condizem com o comportamento da reação que será analisada. 

## Gráficos gerados
<p align="justify"> Para a titulação no modo 1 do ácido acético (pKa = 4.76) com o hidróxido de sódio, ambos com a concentração de 0,1 molar, e o volume do ácido fraco titulado sendo igual a 25 ml, vamos ter o seguindo gráfico gerado pela ferramenta:
<div align="center">
<img width="500" height="400" alt="Curva_de_Titulacão_modo1" src="https://github.com/user-attachments/assets/6cdd22c4-c91b-4e58-9995-958589b8fe00" />
</div>

<p align="justify"> Para a titulação no modo 2 da amônia (pKb = 4.75) com o ácido clorídrico, ambos com a concentração de 0,1 molar, e o volume da base fraca titulada sendo igual a 25 ml, vamos ter o seguinte gráfico gerado pela ferramenta:
<div align="center">
<img width="500" height="400" alt="Curva_de_Titulacão_modo2" src="https://github.com/user-attachments/assets/fec557c1-6d65-4871-a0a6-2e7c1b941e23" />
</div>
     
## **Referências**
* Brown, T.L.; Lemay, H.E.; Murphy, C.J; Woodward, P.M; Stoltzfus, M.W. **Química: a ciência central**. Tradução de: Eloiza Lopes, Tiago Jonas, Sonia Midori Yamamoto; revisão técnica Antonio Gerson Bernardo da Cruz. 13ª edição, São Paulo: Pearson/Prentice Hall,2016.

## Desenvolvedora do Projeto
- **Bruna Fujihashi** - [Bruna Fujihashi](https://github.com/buruna087)<br>
Estudante de Ciência e Tecnologia na Ilum Escola de Ciência.

## Professores 
<img loading="lazy" src="https://github.com/user-attachments/assets/17dfa7bf-5ca9-42df-b63e-917827fc6308" width=115><br><sub> [Prof. Dr. Daneiel Roberto
Cassar](http://lattes.cnpq.br/1717397276752482) </sub></p> <img loading="lazy" src="https://github.com/user-attachments/assets/5be40392-5473-4b8b-b636-a55cbf0114fd" width=115><br><sub> [Prof. Dr. James Moraes de Almeida](http://lattes.cnpq.br/4169321429650165) </sub></p> <img loading="lazy" src="https://github.com/user-attachments/assets/ca8bd41b-c6d0-479c-aacd-a3d2c6b45c0d" width=115><br><sub> [Prof. Dr. Leandro Nascimento Lemos](http://lattes.cnpq.br/8039429508021054) </sub></p> <img loading="lazy" src="https://github.com/user-attachments/assets/08c1d19b-593e-4760-b484-719aa4feffe3" width=115><br><sub> [Profa. Dra. Valeria Spolon Marangoni](http://lattes.cnpq.br/2367731800019171) </sub></p> 

## Agradecimentos
<p align="justify"> Nesta seção dedido agradecimentos especiais a Prof. Dra. Valeria Spolon Marangoni pela revisão dos conceitos químicos por traz do projeto referido.


