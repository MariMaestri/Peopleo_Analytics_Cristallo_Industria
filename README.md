# Diagnóstico de People Analytics: Cristallo Indústria de Vidros

Este projeto de People Analytics foi desenvolvido no Power BI para a Cristallo, uma empresa fictícia, com o objetivo de orientar a decisão da diretoria sobre a abertura de um novo turno de produção. A análise utiliza dados históricos para diagnosticar problemas de retenção e equidade, garantindo que a expansão ocorra de forma sustentável e sem replicar falhas anteriores.

**Este projeto foi desenvolvido em colaboração por:**

* Isabella Soberay
* [Luana Barrios](https://github.com/LuanaBarrios)
* Mariane Maestri

## O Problema de Negócio

A Cristallo conta com 249 colaboradores ativos e registrou 611 desligamentos desde 2002, dos quais 77% ocorreram antes de o funcionário completar um ano de empresa. A diretoria precisa definir nos próximos meses quantas pessoas contratar e quais serão as regras de seleção, integração, remuneração e promoção para o novo turno. Contratar em grande volume sem entender o alto índice de saídas no primeiro ano e as possíveis disparidades salariais representa um grave risco financeiro, trabalhista e de perda de prazo.

## Hipóteses e Perguntas de Negócio

O projeto foi guiado por cinco hipóteses centrais testadas nos dados:

* **Evolução do quadro:** O quadro de colaboradores cresceu de forma contínua, mas a retenção enfraqueceu recentemente.


* **Risco de saída inicial:** Cargos operacionais e estágios concentram o maior risco de desligamento nos primeiros meses.


* **Motivação do turnover:** Saídas precoces ocorrem majoritariamente por iniciativa do colaborador.


* **Equidade salarial:** Mulheres e pessoas negras recebem salários menores em cargos comparáveis.


* **Equidade em promoções:** A taxa de promoção é desproporcionalmente menor para mulheres e pessoas negras.



## Base de Dados

A análise abrange o histórico de 2002 a junho de 2020, totalizando 860 contratos de trabalho. Destes, 249 são colaboradores ativos e 611 são desligados. Métricas de salário e promoção foram calculadas apenas sobre o quadro ativo atual.

## Análise do Dashboard

**Página 1: Início**
Apresenta a capa do projeto com o título "Diagnóstico do Quadro de Pessoal", a pergunta norteadora "Como expandir sem perder gente nem equidade?" e o nome das integrantes da equipe. O menu lateral permite a navegação entre as seções.

<img width="885" height="491" alt="PG 1" src="https://github.com/user-attachments/assets/65141218-00d2-4411-ac74-1b9d35f20ff2" />
<br>
<br>

**Página 2: Visão Geral**
Mapeia a composição atual e a evolução histórica do quadro.

* O quadro atual possui 249 ativos, sendo 38,2% mulheres e 26,1% pessoas pretas e pardas.


* O saldo de movimentações em 2020 é negativo (-17).


* A empresa apresentou crescimento contínuo até 2017 (atingindo 269 colaboradores) e vem encolhendo desde então.


* A área de Operação e Produção concentra 53% do quadro (131 ativos).


* Há uma base experiente na empresa: 45% do quadro (111 pessoas) possui mais de 5 anos de casa.
  
<img width="888" height="498" alt="PG 2" src="https://github.com/user-attachments/assets/d41d2347-cc04-42c9-81a2-17e91de7cc81" />
<br>
<br>

**Página 3: Risco de Turnover**
Analisa os padrões de desligamento para identificar quem sai, quando e por decisão de quem.

* 76,76% de todas as saídas ocorrem no primeiro ano de trabalho, sendo que 30% acontecem em até 90 dias.


* A média de tempo até a saída é de 135 dias.


* Diferente da hipótese inicial, 64,81% das saídas ocorrem por iniciativa da empresa.


* Estagiários apresentam o maior risco, com 78,38% deixando a empresa no primeiro ano.


* O cargo de Operador de Ponte Rolante possui uma taxa crítica de saída de 77,38%.


* Desde 2017, a empresa aumentou o volume de demissões de funcionários com mais de um ano de experiência.

<img width="887" height="496" alt="PG 3" src="https://github.com/user-attachments/assets/f3aefc7e-edc0-4e19-ad60-cbfed5c408bb" />
<br>
<br>

**Página 4: Equidade**
Avalia a distribuição de salários e oportunidades de crescimento por gênero e raça.

* O salário médio dos ativos é de R$ 4 mil, e a taxa geral de promoção é de 72,7%.


* A representatividade negra é de 30% na Operação, mas cai para apenas 10% na diretoria.


* A taxa de promoção revela disparidade racial: 63% para pessoas negras contra 78% para não negras.


* O maior gap salarial entre raças ocorre nas áreas de Supervisão/Coordenação e Comercial/Marketing.


* Apesar das discrepâncias gerais, a análise de nível de cargo mostra que salários são praticamente iguais para pessoas ocupando a mesma função.

<img width="885" height="493" alt="PG 4" src="https://github.com/user-attachments/assets/1da583fe-5b9b-4943-82bb-4d982a97cd47" />
<br>
<br>

**Página 5: Sugestões**
Reúne recomendações estratégicas baseadas em dados para a abertura do novo turno.

1. **Abrir o turno em ondas:** Iniciar com um núcleo de veteranos internos e contratar pessoas de fora gradativamente, mitigando a recente perda de experiência.


2. **Cuidar de todo o primeiro ano:** Implementar testes práticos na seleção e realizar acompanhamentos estruturados aos 30, 90 e 180 dias, visando frear a taxa de saída prematura.


3. **Promover com critérios claros:** Utilizar as vagas do novo turno como uma janela de promoção interna com regras transparentes para corrigir a disparidade nas taxas de promoção de colaboradores negros.


4. **Gerir com dados todo mês:** Transformar o dashboard em uma rotina contínua de gestão e começar a registrar o turno de trabalho, dado que hoje a escala não guarda histórico.

<img width="884" height="492" alt="PG 5" src="https://github.com/user-attachments/assets/faa06bcb-ec2a-4a5c-be3f-5db8aaac1f67" />
