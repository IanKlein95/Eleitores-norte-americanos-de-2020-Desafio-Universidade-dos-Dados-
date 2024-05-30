# Eleitores-norte-americanos-de-2020-Desafio-Universidade-dos-Dados-
Descrição do perfil dos eleitores norte-americanos, do que consideram ser um bom norte-americano e das suas escolhas partidárias em 2020

O dataset contém dados de 5837 respondentes, contendo tanto suas características quanto as respostas que deram à um questionário aplicado por FiveThirtyEight. O link para o dataset é: https://github.com/fivethirtyeight/data/tree/master/non-voters. O objetivo original é entender melhor os eleitores norte-americanos, suas caractéristicas e desejos políticos no contexto das eleições de 2020. Aqui, a proposta é mapear o perfil da amostra, o que eles consideram ser um bom norte-americano e as suas escolhas e afinidades partidárias. Além disso, propõe-se um público alvo para os republicanos focarem em angariar mais votos com base em insights retirados das análises. Elas foram feitas por meio do Excel. 

As variáveis são:
- voter_category:
          always: respondente votou em todas as eleições, ou menos uma.
          sporadic: respondente votou em ao menos duas eleições, mas menos do que todas menos uma.
          rarely/never: respondente votou em uma eleição ou nenhuma.
- PPAGE: idade do respondente
- GENDER: gênero do respondente
- EDUC: nível de escolaridade
- RACE: raça do respondente
- INCOME_CAT: faixa de renda familiar
- RESPID: ID única do respondente
- WEIGHT: peso

  Ainda, o dataset contém as respostas das perguntas feitas. As perguntas se encontram no link do dataset posto acima.

  # Perfil dos eleitores da amostra

  ![Gênero](https://github.com/IanKlein95/Eleitores-norte-americanos-de-2020-Desafio-Universidade-dos-Dados-/assets/125080692/399980e3-0199-46e0-946d-c5f883f5140c)

  Tem-se que a amostra é bem dividida entre gêneros.

  ![Raça](https://github.com/IanKlein95/Eleitores-norte-americanos-de-2020-Desafio-Universidade-dos-Dados-/assets/125080692/b4882019-fffe-471d-9724-0e2e90e33e8f)

  A maioria dos eleitores são brancos e cerca de 30% deles são negros ou hispânicos. Uma minoria é de outra raça ou miscigenado.

  ![Escolaridade](https://github.com/IanKlein95/Eleitores-norte-americanos-de-2020-Desafio-Universidade-dos-Dados-/assets/125080692/908e4e2f-dc1e-405c-a671-c1e89f2d8616)

  A proporção dos níveis de escolaridade são próximas, com uma leve maioria de eleitores com nível superior completo.

  ![Faixa de renda](https://github.com/IanKlein95/Eleitores-norte-americanos-de-2020-Desafio-Universidade-dos-Dados-/assets/125080692/91d91de3-de25-42cd-b70b-15477d6adf28)

  O mesmo pode se dizer das proporções das faixas de renda, com uma leve maioria daqueles eleitores que ganham entre 75 e 125 mil dólares.

  ![Participação eleitoral](https://github.com/IanKlein95/Eleitores-norte-americanos-de-2020-Desafio-Universidade-dos-Dados-/assets/125080692/3a7148ab-cd60-49a6-9ddc-a3944ad6d83a)

  A maioria dos eleitores vota esporadicamente, seguidos por eleitores que votam sempre. A proporção dos eleitores que votam raramente/nunca fica em último, mas próximo da daqueles que votam sempre.

  ![Idade](https://github.com/IanKlein95/Eleitores-norte-americanos-de-2020-Desafio-Universidade-dos-Dados-/assets/125080692/66de1776-c281-42ac-aeff-d775d11fd7c1)

  A média de idade dos eleitores é de 52 anos, uma média elevada. A idade que divide a amostra na metade é 54 anos, o que reforça a impressão de que a amostra é composta em sua maioria por eleitores mais velhos. O desvio padrão é de 17 anos. A idade mínima é 22 anos. A idade máxima é 94 anos. 50% dos eleitores têm entre 36 e 54 anos.

  Cruzando estas características, tem-se que:

  ![raçaxgenero-escolaridadexgenero](https://github.com/IanKlein95/Eleitores-norte-americanos-de-2020-Desafio-Universidade-dos-Dados-/assets/125080692/86d5d401-1dcd-46bb-b066-92d56ae4e574)

  O predomínio de eleitores brancos se repete na seleção quando a amostra é separada por gênero. No que diz, respeito ao nível de escolaridade, mais homens têm ensino superior completo do que mulheres proporcionalmente. Da mesma forma, mais mulheres completaram só até o ensino médio do que os homens proporcionalmente.

  ![rendaxgenero-participaçaoxgenero](https://github.com/IanKlein95/Eleitores-norte-americanos-de-2020-Desafio-Universidade-dos-Dados-/assets/125080692/aa120c8b-828f-4f51-8634-08480a5223c5)

  Nas próprias faixas de renda, mais homens ganham mais de 125 mil dólares por ano proporcionalmente. Mais mulheres ganham menos de 40 mil dólares por ano proporcionalmente. Já em relação à proporção de participação eleitoral entre gêneros, mantém-se quase a mesma daquela vista individualmente.

  ![idadexgenero](https://github.com/IanKlein95/Eleitores-norte-americanos-de-2020-Desafio-Universidade-dos-Dados-/assets/125080692/a78af857-5274-4388-a445-ee160d6be6ea)

  Da mesma forma, as medidas de tendência central são similares com as medidas analisadas individualmente.

  ![raçaxescolaridade-raçaxrenda](https://github.com/IanKlein95/Eleitores-norte-americanos-de-2020-Desafio-Universidade-dos-Dados-/assets/125080692/58cb65e5-6193-472c-bc40-55d8ceee5307)

  Nas próprias proporções de raça, a maioria dos eleitores de outra raça/miscigenados tem ensino superior, seguido pelos eleitores brancos. Dentre os eleitores negros e hispânicos, as proporções dos níveis de escolaridade são bem divididas. O mesmo destaque dos eleitores de outra raça/miscigenados e brancos aparece dentre as proporções de eleitores que ganham mais de 125 mil dólares. Os negros e hispânicos tendem a receber ligeiramente pior na faixa de renda de menos de 40 mil dólares.

  ![raçaxparticipacao-raçaxidade](https://github.com/IanKlein95/Eleitores-norte-americanos-de-2020-Desafio-Universidade-dos-Dados-/assets/125080692/3d9dc40a-9125-4dd4-9b91-138a15361c86)

  Dentre todas as raças, a maioria vota esporadicamente. Enquanto mais brancos e negros votam sempre, hispânicos e pessoas de outras raças/miscigenadas votam raramente/nunca proporcionalmente.
As pessoas hispânicas e de outras raças/miscigenadas são levemente mais novas do que as pessoas brancas e negras.

  ![escolaridadexrenda-escolaridadexparticipaçao](https://github.com/IanKlein95/Eleitores-norte-americanos-de-2020-Desafio-Universidade-dos-Dados-/assets/125080692/7fe88556-f48c-4410-8af6-82a4881576a7)

  Vê-se que aqueles eleitores da amostra com maior nível de escolaridade tendem a ganhar mais e que aqueles com menor nível de escolaridade tendem a ganhar menos. A participação eleitoral esporádica é superior entre todas os níveis de escolaridade. Eleitores com ensino médio ou básico tendem a não participar sempre do processo eleitoral.

   Verificando se existe correlação entre nível de escolaridade e faixa de renda e nível de escolaridade e participação eleitoral:

  ![corr rendaxescolaridade](https://github.com/IanKlein95/Eleitores-norte-americanos-de-2020-Desafio-Universidade-dos-Dados-/assets/125080692/d7c5dbd1-f468-4315-8b44-5bf372259ef2)

  Existe correlação positiva moderada entre nível de escolaridade e renda, o que demonstra coincidência de pessoas com maior nível educacional e maiores níveis de renda.

  ![corr escolaridadexparticipaçao](https://github.com/IanKlein95/Eleitores-norte-americanos-de-2020-Desafio-Universidade-dos-Dados-/assets/125080692/178462bd-5605-43a3-8a58-177e2212a365)

  Existe correlação positiva muito fraca entre nível educacional e participação eleitoral, o que indica que um maior nível de escolaridade não coincide com uma participação eleitoral mais ativa.

  ![idadexparticipaçao](https://github.com/IanKlein95/Eleitores-norte-americanos-de-2020-Desafio-Universidade-dos-Dados-/assets/125080692/277b777a-b551-4677-8c18-eeeebb3dd2bf)

  Eleitores mais novos parecem tender a participar raramente/nunca, tendo uma média e uma mediana mais baixa do que as dos outros. A distribuição das idades entre aqueles que votam sempre e esporadicamente são similares. Verificando se existe alguma correlação:

  ![corr idadexparticipaçao](https://github.com/IanKlein95/Eleitores-norte-americanos-de-2020-Desafio-Universidade-dos-Dados-/assets/125080692/8c4d5244-56a0-4654-a0c4-0a06f51bd6b8)

  Existe correlação positiva moderada entre idade e participação eleitoral, o que demonstra coincidência entre maior idade e maior comparecimento às urnas. Entretanto, deve-se considerar que a amostra tem uma média e mediana de idade altas.

  # O que os eleitores consideram ser um bom americano

  O questionário aplicado utiliza uma escala likert, no qual:
  - -1 = Não sabe/Não respondeu
  - 1 = considera o item muito importante
  - 2 = considera o item importante
  - 3 = considera o item pouco importante
  - 4 = considera o item nada importante

  Dentre os eleitores não-brancos (negros, hispânicos e outras raças/miscigenados:

  ![votar](https://github.com/IanKlein95/Eleitores-norte-americanos-de-2020-Desafio-Universidade-dos-Dados-/assets/125080692/86cfc5cd-71aa-499b-b1dd-d67daa6f8cd5)

  A maioria considera muito importante ou importante.

  ![jurado](https://github.com/IanKlein95/Eleitores-norte-americanos-de-2020-Desafio-Universidade-dos-Dados-/assets/125080692/5ebb9dbd-ca2f-4909-a8de-2f5991656008)

  Aproximandamente 80% dos eleitores não-brancos considera muito importante ou importante desempenhar o dever cívico de ser jurado.

  ![bem informado](https://github.com/IanKlein95/Eleitores-norte-americanos-de-2020-Desafio-Universidade-dos-Dados-/assets/125080692/ef5945ee-784f-4a59-8653-4180ddfeb1f1)

  Aproximandamente 87% dos eleitores não-brancos considera muito importante ou importante estar bem informado sobre o que acontece na política.

  ![bandeira](https://github.com/IanKlein95/Eleitores-norte-americanos-de-2020-Desafio-Universidade-dos-Dados-/assets/125080692/f05d1f19-8d2c-48b8-9808-fd09b8cd7b17)

  Aproximadamente 53% deles considera muito importante ou importante ostentar a bandeira. Aproximadamente 46% deles considera pouco importante ou nada importante o mesmo.

  ![censo](https://github.com/IanKlein95/Eleitores-norte-americanos-de-2020-Desafio-Universidade-dos-Dados-/assets/125080692/f62db125-9181-4b44-88e5-2ccb5f3312c6)

  A maioria absoluta considera muito importante ou importante participar do Censo.

  ![juramento](https://github.com/IanKlein95/Eleitores-norte-americanos-de-2020-Desafio-Universidade-dos-Dados-/assets/125080692/6958b88e-7c58-4d1a-97b2-687dff91410a)

  Aproximadamente 71% considera muito importante ou importante saber o juramento à bandeira. Aproximadamente 28% considera pouco ou nada importante o mesmo.

  ![exército](https://github.com/IanKlein95/Eleitores-norte-americanos-de-2020-Desafio-Universidade-dos-Dados-/assets/125080692/fb30ca19-6be0-4911-864d-65afb0a52a99)

  Aproximadamente 86% consdiera muito importante ou importante apoiar o exército.

  ![opinião](https://github.com/IanKlein95/Eleitores-norte-americanos-de-2020-Desafio-Universidade-dos-Dados-/assets/125080692/c41c5fc8-49ee-4436-af89-2f73a40d46c4)

  A maioria (aproximadamente 92%) considera importante ou muito importante respeitar a opinião divergente.

  ![Deus](https://github.com/IanKlein95/Eleitores-norte-americanos-de-2020-Desafio-Universidade-dos-Dados-/assets/125080692/a5f22e2a-cd72-4ff3-b2c7-917ea85a6fbf)

  Aproximadamente 70% considera importante ou muito importante acreditar em Deus. Aproximadamente 29% considera pouco ou nada importante o mesmo.

  ![protestar](https://github.com/IanKlein95/Eleitores-norte-americanos-de-2020-Desafio-Universidade-dos-Dados-/assets/125080692/4fb3aed6-14ec-4e2d-abe6-7aa44c64f86f)

  Aproximandamente 80% considera muito importante ou importante o direito de protestar.

  Considerando a importância do ato de votar, de ostentar a bandeira americana e de apoiar o exército, existe maior unidade dos eleitores não-brancos em torno do ato de votar como muito importante ou importante. Ostentar a bandeira é a opção que possui mais proporção no sentido contrário (pouco importante ou nada), com um pouco mais de 40%.

  Comparando essas perguntas em relação ao poder aquisitivo, mas para o mesmo público não-branco:

  ![votar(faixa](https://github.com/IanKlein95/Eleitores-norte-americanos-de-2020-Desafio-Universidade-dos-Dados-/assets/125080692/a0e5519e-a32c-49f3-9d4e-4266599c48f2)

  Embora se verifique que nas faixas de renda menores, votar ainda é considerado muito importante ou importante, ocorrem as proporções diminuem. Ocorre aumento, mesmo que mínimo, dentre aqueles das menores faixas de renda que consideram votar pouco ou nada importante.

  ![ostentar(faixa)](https://github.com/IanKlein95/Eleitores-norte-americanos-de-2020-Desafio-Universidade-dos-Dados-/assets/125080692/ac9a05b3-a508-4493-8c5d-3ab8333c8d7a)

  A proporção daqueles eleitores que consideram ostentar a bandeira muito importante ou importante também sobe proporcionalmente conforme as faixas de renda são menores. Da mesma forma, a proporção dos eleitores que consideram pouco ou nada importante aumenta levemente conforme se analisa as faixas de renda mais elevadas.

  ![apoiar(faixa)](https://github.com/IanKlein95/Eleitores-norte-americanos-de-2020-Desafio-Universidade-dos-Dados-/assets/125080692/eff363f8-3c9b-49e2-be7d-68b79abe2200)

  As proporções de significação do ato de votar se mantêm em grande medida ao longo das faixas de renda, com leves diminuições da importância nas classes mais baixas e leves aumentos da pouca ou nada importância desse ato.

  Agora, olhando para a importância da tolerância dentre diferentes faixas etárias para esse grupo:

  ![faixaetariaxtolerancia](https://github.com/IanKlein95/Eleitores-norte-americanos-de-2020-Desafio-Universidade-dos-Dados-/assets/125080692/d5e71207-cac6-4b2f-a04f-b3df8b07f71a)

  A geração de 51 anos ou mais é a que, proporcionamente, mais tem eleitores que consideram muito importante ou importante. Contudo, as outras gerações também se destacam nessa escala. A faixa etária 18-30 anos tem uma proporção de eleitores que pouco se importam que é quase o dobro daquela da faixa etária de 51 anos ou mais, embora a proporção geral seja pequena.

  # Escolhas partidárias

  






  

  









  

  



  

  

  


  





  






  

  
