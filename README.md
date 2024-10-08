<Div align="center" >

## Introdução

</Div>

<Div align="justify" >

<img align="right" src="img/ThallesTorres.jpg" alt="Foto de perfil" width="300"/>

Tenho uma paixão pela área de programação desde o ensino médio. Comecei a fazer um curso técnico de TI e, com isso, fui me apaixonando mais pela área. Nesse período, realizei projetos e fiz cursos para aprofundar-me na área.

Nessa jornada na área criei gosto por analisar e solucionar problemas, tanto que hoje tenho como passatempo a área de manutenção de placas eletrônicas.

Este portfólio tem o objetivo de destacar os diversos projetos desenvolvidos ao longo dos semestres durante o curso de Análise e Desenvolvimento de Sistemas na FATEC SJC.
</Div>

<Div align="center" >

<br>

## Contato

  <a href= "www.linkedin.com/in/thalles-torres-83449a285" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 

<br />  

## Conhecimentos

![Static Badge](https://img.shields.io/badge/Git-%23183359)
![Static Badge](https://img.shields.io/badge/Java-%23183359)
![Static Badge](https://img.shields.io/badge/Python-%23183359)
![Static Badge](https://img.shields.io/badge/Html-%23183359)
![Static Badge](https://img.shields.io/badge/Css-%23183359)
![Static Badge](https://img.shields.io/badge/TypeScrip-%23183359)
![Static Badge](https://img.shields.io/badge/MySql-%23183359)
![Static Badge](https://img.shields.io/badge/MongoDB-%23183359)
![Static Badge](https://img.shields.io/badge/Docker-%23183359)
![Static Badge](https://img.shields.io/badge/AWS-%23183359)
![Static Badge](https://img.shields.io/badge/Linux-%23183359)

<br>
<br>

## Projetos

</Div>

## Projeto 1 - 2019-2

**Parceiro acadêmico:** [Fatec São José dos Campos - Prof. Jessen Vidal](https://fatecsjc-prd.azurewebsites.net/)

<Div align="justify" >

<img align="right" src="img/API1.png" alt="Foto de perfil" width="300"/>

O Smartparking é uma solução tecnológica baseada em IoT (Internet das Coisas) que visa resolver uma significativa deficiência em mercados, shoppings e grandes estacionamentos. Seu principal objetivo é auxiliar os motoristas a encontrar vagas de estacionamento de forma simples e rápida. O sistema funciona por meio de sensores ultrassônicos instalados em cada vaga, os quais estão conectados a uma placa Arduino. Esses sensores enviam em tempo real para os usuários do aplicativo informações sobre as vagas livres e ocupadas, simplificando assim o processo de encontrar uma vaga de estacionamento.

</Div>

## Tecnologias Utilizadas

Para desenvolver o projeto Smartparking, utilizamos uma combinação de tecnologias de hardware, software e banco de dados. As principais tecnologias incluíram:

- **Arduino Uno:** Usado como o cérebro do projeto, o Arduino contava as vagas do estacionamento usando o sensor ultrassônico para detectar veículos. Ele também enviava dados via Bluetooth para o aplicativo Android.

- **Sensor ultrassônico:** Escolhido por sua capacidade de medir a distância a objetos, o sensor ultrassônico facilitou a detecção de veículos estacionados.

- **Módulo Bluetooth:** Utilizado para a comunicação entre o Arduino e o aplicativo móvel devido à sua fácil integração.

- **AppInventor:** Plataforma online para desenvolvimento de aplicativos por meio de programação em blocos. Criamos dois aplicativos: um principal para os usuários verificarem as vagas disponíveis e outro para gerar métricas a partir da opinião dos usuários sobre o protótipo.

- **Firebase:** Usado para armazenar dados de usuários cadastrados e métricas geradas. O Firebase foi escolhido pela sua simplicidade e por ser um banco de dados NoSQL.

- **C++:** Linguagem de programação utilizada para escrever o código do Arduino e suas integrações.

## Contribuições Pessoais

Minhas contribuições incluíram a programação do Arduino, integração com o sensor ultrassônico e o aplicativo Android usando Bluetooth. Além disso, trabalhei no desenvolvimento do aplicativo Core e integrações com o Firebase usando AppInventor.

### Hard Skills

- Programação de placas Arduino e NodeMcu
> Sei fazer com autonomia
- Integrações Bluetooth
> Sei fazer com autonomia
- Integrações Firebase
> Sei fazer com autonomia
- Desenvolvimento em blocos com AppInventor
> Sei fazer com autonomia

### Soft Skills

- Adaptabilidade 
> Diante do desafio de trabalhar com tecnologias como Arduino e App Inventor, que eram novidade para todos os membros da equipe, demonstrei grande capacidade de adaptação, rapidamente assimilando novos conceitos e aplicando-os na prática. Essa flexibilidade foi fundamental para superar os obstáculos e entregar o projeto com sucesso.
- Trabalho em equipe
> Embora não houvesse um líder formal na equipe, contribuí ativamente para um ambiente colaborativo, compartilhando meus conhecimentos e aprendizados com os demais membros. A troca de ideias e a colaboração mútua foram essenciais para o desenvolvimento do projeto.
- Comunicação
> Ao apresentar o projeto para a turma e para o professor, aprimorei minhas habilidades de comunicação, explicando de forma clara e concisa as soluções técnicas adotadas e os resultados obtidos.
#

## Projeto 2 - 2020-1

**Parceiro acadêmico:** [SPC Brasil](https://www.spcbrasil.org.br/)

**Projeto:** [MetaApp](https://github.com/ThallesTorres/Projeto_SPC)

#### Visão do Projeto

<Div align="justify" >
  
Com a transição para o novo modelo de operação do Cadastro Positivo, o cliente enfrentou a necessidade premente de redesenhar sua gestão de informações para algo mais eficaz e com garantia de qualidade. Ele buscava uma solução que não apenas utilizasse os dados da forma mais correta possível, mas também gerasse valor a partir dessas informações.

O desafio consistia em entregar ao cliente um produto capaz de extrair dados de arquivos .csv e produzir relatórios com indicadores de qualidade especificados pelo cliente. A solução proposta oferecia uma interface intuitiva que permitia a geração desses relatórios, além de facilitar o armazenamento local por meio de um executável.

</Div>

#### Requisitos Funcionais (com base nos indicadores de qualidade do cliente)
- Integridade 
- Recência
- Confidencialidade
- Confiabilidade
- Completude
- Consistência

#### Requisitos Não Funcionais
- Disponibilizar uma aplicação desktop
- Análise e tratamento de arquivos .xlsx e .csv

**Visualização do relatório:**

![](https://i.imgur.com/TGv7iFU.gif)

## Tecnologias Utilizadas

- **HTML e CSS**: Utilizados no desenvolvimento da interface gráfica para o usuário.

- **Python**: Utilizado no back-end do projeto, sendo responsável pelo processo que os dados contidos nos documentos .csv eram submetidos: leitura, validação, correção e armazenamento.

- **Jupyter Notebook**: Utilizado com a finalidade de tornar o desenvolvimento mais dinâmico, facilitando a visualização e compartilhamento do código do projeto.

## Contribuições Pessoais

Fui encarregado de desenvolver tanto o front-end do projeto, utilizando HTML e CSS para criar uma interface amigável para o usuário, quanto de analisar os dados recebidos pelo back-end. A minha responsabilidade era garantir que as informações fossem apresentadas de forma simples, com uma legenda clara, e que os resultados processados pelo back-end fossem exibidos através de gráficos e porcentagens de maneira compreensível para o usuário.

### Hard Skills

- **HTML e CSS**: Utilizados no desenvolvimento da interface gráfica para o usuário.
> Sei fazer com autonomia
- **Python**: Utilizado no back-end do projeto para leitura, validação, correção e armazenamento de dados.
> Sei fazer com autonomia

### Soft Skills

- Proatividade 
> Demonstrando proatividade, iniciei estudos independentes em programação, o que me permitiu contribuir de forma mais efetiva para o desenvolvimento do back-end do projeto. Essa iniciativa foi fundamental para superar os desafios da manipulação de dados e garantir a entrega de um produto de qualidade.
- Resolução de problemas
> Ao lidar com a complexidade da manipulação de dados em grande escala, desenvolvi habilidades de resolução de problemas, buscando soluções eficientes para garantir a qualidade dos resultados. 
#

## Projeto 3 - 2020-2

**Parceiro acadêmico:** [Visiona Tecnologia Espacial S.A.](https://www.visionaespacial.com.br/)

**Projeto:** [JumboETL](https://github.com/DaviNeves0/ETL_Visiona)

#### Visão do Projeto

<Div align="justify" >
  
O projeto que desenvolvi neste semestre atendia à necessidade do nosso cliente, uma empresa parceira, que buscava uma ferramenta capaz de desempenhar funções semelhantes a um "mini-ETL". A principal funcionalidade exigida era a capacidade de extrair dados de um arquivo do tipo shapefile, armazená-los em um banco de dados e também realizar o processo inverso.

O JumboETL, a solução que ofereci, é uma aplicação web que permite a manipulação de dados georreferenciados, simulando um processo ETL (Extract, Transform, Load) e sendo acessível em qualquer dispositivo com suporte a navegadores web. O desenvolvimento do JumboETL foi pensado para proporcionar uma experiência de usuário simples e intuitiva, facilitando o upload dos dados do arquivo shapefile e a criação de um novo arquivo shapefile a partir dos dados armazenados no banco de dados.

</Div>

#### Requisitos Funcionais
 - Carga de dados geográficos (ponto, linha e polígono) e seus atributos alfanuméricos em tabelas existentes de banco de dados geográficos;
 - Recuperação de dados geográficos (ponto, linha e polígono) e seus atributos alfanuméricos armazenados em banco de dados geográficos.

#### Requisitos Não Funcionais
 - Ser um sistema Web;
 - Linguagens Python ou Java;
 - Banco de Dados Geográficos PostGIS.

**Telas do sistema JumboETL:**

![](https://i.imgur.com/0AO8IiY.jpg)

## Tecnologias Utilizadas

- HTML/CSS - para estruturação da página Web
- Bibliotecas React, Axios, Ant Design, React Suite - para o Front-end
- PostgreSQL e extensão PostGIS - para armazenar os dados georreferenciados
- Java, Maven, Sprint, Tomcat - para estrutura do Back-end.
- Geotools e Gdal - para trabalhar com os dados geoespaciais

## Contribuições Pessoais

No projeto, atuei no front-end com HTML/CSS e bibliotecas como React, Axios, Ant Design e React Suite. No back-end, utilizei Java, Maven, Spring e Tomcat, integrando o PostgreSQL com PostGIS para armazenar dados georreferenciados. Também utilizei Geotools e Gdal para manipulação de dados geoespaciais, contribuindo assim para o desenvolvimento completo e funcional do sistema JumboETL.

### Hard Skills

- **HTML e CSS**
> Sei utilizar com autonomia
- **Java**
> Sei utilizar com autonomia
- **PostgreSQL**
> Sei utilizar com autonomia
- **Geotools e Gdal**
> Sei utilizar com autonomia


### Soft Skills

- Perseverança 
> Diante dos desafios apresentados pelo projeto, como a complexidade da linguagem Java e a manipulação de dados geográficos, demonstrei perseverança e determinação para superar os obstáculos e entregar um produto completo e funcional.
- Resolução de problemas
> Ao lidar com a complexidade da integração de diferentes tecnologias e da manipulação de dados geográficos, desenvolvi habilidades de resolução de problemas, buscando soluções criativas e eficientes para os desafios encontrados. A capacidade de analisar o problema de forma sistemática e identificar a causa raiz foi fundamental para o sucesso do projeto.


#

## Projeto 4 - 2023-2

**Parceiro acadêmico:** [GREENNEAT](https://greenneat.eco.br/)

**Projeto:** [Quantum Team](https://github.com/QuantumTeam23/API--4-ADS)

#### Visão do Projeto

<Div align="justify" >
  
O projeto visa criar uma plataforma integrada para incentivar a participação na cadeia de descarte e reciclagem de óleo de fritura usado. Esta plataforma gerenciará de forma eficiente os créditos obtidos por estabelecimentos cadastrados, utilizados como contrapartida na coleta pelos parceiros da Greenneat. Buscamos estabelecer um ecossistema colaborativo e sustentável, simplificando o controle de descarte e coleta para Parceiros Coletores e Estabelecimentos Fornecedores. Os créditos acumulados poderão ser usados em transações na loja virtual, promovendo práticas ambientalmente responsáveis e contribuindo para a economia circular.

</Div>

#### Requisitos Funcionais
 - Implementação de formulário para cadastro de parceiros Greenneat.
 - Desenvolvimento de formulário para cadastro de estabelecimentos onde o óleo será coletado.
 - Criação de um sistema de transação de créditos Greenneat.
 - Desenvolvimento de painéis específicos para usuários parceiros, estabelecimentos e administração.
 - Criação de um dashboard com rankings.
 - Implementação de um comparador de preços entre óleo virgem, óleo usado e créditos Greenneat.

#### Requisitos Não Funcionais
- Garantia de bom tempo de resposta e execução eficiente nas transações.
- Interface amigável, com boa usabilidade para todos os tipos de usuários.
- Inclusão de métricas para monitorar e analisar o desempenho e comportamento do sistema.

**Projeto finalizado**

![](https://github.com/QuantumTeam23/API--4-ADS/blob/main/Imagens/apresentacao4Sprint.gif)

## Tecnologias Utilizadas

- Front-end: React
- Back-end: Node.js
- Linguagem de Programação: TypeScript
- Banco de Dados: PostgreSQL
- Ferramentas: Git, GitHub, Visual Studio Code, Figma, Canva

## Contribuições Pessoais

No projeto, desempenhei um papel fundamental no desenvolvimento do front-end utilizando React, uma biblioteca JavaScript amplamente reconhecida pela sua eficiência e versatilidade na criação de interfaces web dinâmicas. Utilizando também TypeScript, pude garantir uma maior segurança e consistência no código, facilitando a manutenção e a escalabilidade do sistema.

Além disso, trabalhei na integração de ferramentas como Figma e Canva para a criação de designs e layouts visualmente atraentes e funcionais. Utilizando o Visual Studio Code como ambiente de desenvolvimento e o Git/GitHub para controle de versão e colaboração, contribuí para garantir a qualidade e a eficiência do projeto do início ao fim.

### Hard Skills

- React
> Sei utilizar com autonomia
- Node.js
> Sei utilizar com ajuda
- TypeScript
> Sei utilizar com autonomia
- PostgreSQL
> Sei utilizar com ajuda


### Soft Skills

- Resiliência
> Após uma pausa de dois anos e meio, retornei aos estudos com determinação, superando os desafios de retomar a programação e me adaptar a novas tecnologias. Essa experiência fortaleceu minha resiliência e capacidade de lidar com situações adversas.
- Adaptabilidade
> Aprender TypeScript e suas tecnologias, além de me integrar a uma nova equipe, exigiu que eu fosse flexível e capaz de aprender rapidamente. Essa adaptabilidade me permitiu contribuir ativamente para o sucesso do projeto, mesmo em um ambiente novo e desafiador.
- Trabalho em equipe
> A experiência de trabalhar em uma equipe nova e acolhedora me permitiu desenvolver minhas habilidades de colaboração e comunicação. A troca de ideias e o apoio mútuo foram fundamentais para o sucesso do projeto.
#

## Projeto 5 - 2024-1

**Parceiro acadêmico:** [Oracle](https://www.oracle.com/br/partnernetwork/expertise/)

**Projeto:** [New Tech](https://github.com/NewTechh/API-5-ADS)

#### Visão do Projeto

<Div align="justify" >
  
O projeto integrador do 5º semestre do curso de Análise e Desenvolvimento de Sistemas foi realizado em parceria com a Oracle. O objetivo foi criar um sistema de gestão de parceiros para dispositivos móveis, responsável por cadastrar novos parceiros, gerenciar atualizações, acompanhar o desenvolvimento de conhecimento e expertise, e fornecer relatórios. A aplicação exibe todos os parceiros cadastrados, suas trilhas de conhecimento e progressão, além de incluir funcionalidades de gerenciamento com diferentes níveis de acesso para administradores.

</Div>

#### Requisitos Funcionais
 - Autenticação de usuários.
 - Cadastro de consultores de alianças.
 - Visualização de usuários.
 - Monitoramento do desempenho dos parceiros por trilhas de conhecimento (Tracks).
 - Interface personalizada para administradores.
 - Interface personalizada para consultores de alianças.

#### Requisitos Não Funcionais
- Segurança: Implementação de mecanismos robustos de segurança para proteger os dados dos usuários e parceiros.
- Manutenibilidade: O código deve ser escrito de forma clara e modular para facilitar futuras manutenções e atualizações.
- Documentação: Manter uma documentação abrangente e atualizada para desenvolvedores e usuários finais.

**Projeto finalizado**

![Equipe NewTech - 3 Sprint (720p60)](https://github.com/ThallesTorres/Portfolio_TG_ADS_FATEC/assets/57546200/526ba6af-1eb0-4604-adc2-b886a0d28c27)


## Tecnologias Utilizadas

- Front-end: React Native
- Back-end: Node.js
- Linguagem de Programação: TypeScript
- Banco de Dados: PostgreSQL, MongoDB
- Ferramentas: Git, GitHub, Visual Studio Code, Figma, Canva

## Contribuições Pessoais

No projeto, concentrei meus esforços principalmente no desenvolvimento do front-end usando React Native e TypeScript. Isso resultou na criação de interfaces móveis dinâmicas e seguras, incluindo telas como login, cadastro de parceiros e consultores de alianças, além de um dashboard para monitorar o desempenho dos parceiros.
Além disso, participei do desenvolvimento do back-end com Node.js e TypeScript, implementando funcionalidades cruciais, como autenticação de usuários e gerenciamento de dados.

### Hard Skills

- React Native
> Sei utilizar com autonomia
- Node.js
> Sei utilizar com autonomia
- TypeScript
> Sei utilizar com autonomia
- PostgreSQL
> Sei utilizar com autonomia
- MongoDB
> Sei utilizar com ajuda


### Soft Skills

- Aprendizagem rápida 
> A experiência com React Native me proporcionou a oportunidade de aprimorar minhas habilidades de aprendizado rápido, adaptando-me rapidamente a novas tecnologias e frameworks, o que é fundamental em um mercado em constante evolução.
- Resolução de problemas
> Ao enfrentar desafios como a otimização do desempenho e a compatibilidade com diferentes dispositivos, desenvolvi habilidades de resolução de problemas, buscando soluções criativas e eficientes para garantir a qualidade do aplicativo.
