# Engenharia de Software #
## Disciplina: Arquitetura de Computadores
### Professor: Leandro de Mattos Ferreira
### Descrição:
Conceitos básicos de computadores. Evolução histórica e principais componentes.
### Propósito:
Ilustrar a origem e a evolução dos computadores para a compreensão do funcionamento dos atuais sistemas computacionais.

---
### 8 Módulos maiores:
- ##### Tema 1. Introdução
- ##### Tema 2: Base Computacional

    | Módulo | Tema | Assunto |
    | ------ | ------ | ------ |
    | módulo 1 | 1 | Desenvolvimento do computador em 4 gerações | 
    | módulo 1 | 2 | Computação no cotidiano |
    | módulo 1 | 3 | Tendências |
    | módulo 1 | 4 | Verificando Aprendizado |
    | ------ | ------ | ------ |
    | módulo 2 | 1 | Hardware e Software  | 
    | módulo 2 | 2 | Principais Componentes de Hardware dos computadores |
    | módulo 2 | 3 | Software |
    | módulo 2 | 4 | Tendências |
    | ------ | ------ | ------ |
    | módulo 3 | 1 | O Sistema Operacional  | 
    | módulo 3 | 2 | Funções do Sistema Operacional |
    | módulo 3 | 3 | Histórico |
    | módulo 3 | 4 | Tendências |
    | ------ | ------ | ------ |
    | módulo 4 | 1 | Origem da Internet  |
    | módulo 4 | 2 | A internet |
    
- ##### Tema 3: Componentes de hardware

    | Módulo | Tema | Assunto |
    | ------ | ------ | ------ |
    | módulo 01 | 1 | Sistemas de Cmoputação  | 
    | módulo 01 | 2 | Linguagem de programação |
    | módulo 01 | 3 | Organização de um sistema de computação |
    | módulo 01 | 4 | Tendências |
    | ------ | ------ | ------ |
    | módulo 02 | 1 | Sistemas de Subprocessamento  | 
    | módulo 02 | 2 | Memória |
    | módulo 02 | 3 | Subsistema de entrada e saída (E/S |
    | módulo 02 | 4 | Tendências |
    | ------ | ------ | ------ |
    | módulo 03 | 1 | Sistemas Operacional  |
    | módulo 03 | 2 | Linguagem de programação |

- ##### Tema 4: Representação de dados

    | Módulo | Tema | Assunto |
    | ------ | ------ | ------ |
    | módulo 01 | 1 | Unidades de informação  | 
    | módulo 01 | 2 | Representação das informações no computador |
    | ------ | ------ | ------ |
    | módulo 02 | 1 | Sistemas de Numeração  | 
    | módulo 02 | 2 | Operação Aritmética com números inteiros em qualquer base |
    | ------ | ------ | ------ |
    | módulo 03 | 1 | Conversão entre sistemas de numeração  |
    | módulo 03 | 2 | Tabela de representação de dados | 

- ##### Tema 5. Lógica Digital

    | Módulo | Tema | Assunto |
    | ------ | ------ | ------ |
    | módulo 01 | 1 | Portas lógicas e lógica booleana  | 
    | módulo 01 | 2 | Tabela verdade |
    | módulo 01 | 3 | Operadores e portas lógicas básicas | 
    | módulo 01 | 4 | Outras portas lógicas fundamentais | 
    | ------ | ------ | ------ |
    | módulo 02 | 1 | Expressões Lógicas  | 
    | módulo 02 | 2 | Avaliação de uma expressão lógica |
    | módulo 02 | 3 | Equivalências de funções lógicas |
    | ------ | ------ | ------ |
    | módulo 03 | 1 | Propriedades da álgebra de Boole |

- ##### Tema 6: Processamento em Paralelo

    | Módulo | Tema | Assunto |
    | ------ | ------ | ------ |
    | módulo 01 | 1 | Evolução dos computadores | 
    | módulo 01 | 2 | Paralelismo em nível de instruções e processadores superescalares |
    | ------ | ------ | ------ |
    | módulo 02 | 1 | Múltiplos processadores | 
    | módulo 02 | 2 | Coerência de cache |
    | ------ | ------ | ------ |
    | módulo 03 | 1 | Computadores Multicore |
    | módulo 03 | 2 | Desempenho do Hardware | 
    | módulo 03 | 3 | Desempenho do Software |
    | módulo 03 | 4 | Organização Multicore |

- ##### Tema 7: Arquitetura Cisc X Risc

    | Módulo | Tema | Assunto |
    | ------ | ------ | ------ |
    | módulo 01 | 1 | Vamos começar! | 
    | módulo 01 | 2 | Arquitetura CISC |
    | módulo 01 | 3 | Analogia da Hamburgueria |
    | ------ | ------ | ------ |
    | módulo 02 | 1 | Arquitetura RISC | 
    | módulo 02 | 1 | Retorno a Analogia da Hamburgueria | 
    | módulo 02 | 3 | Comparação CISC versus RISK |
    | módulo 02 | 4 | Tendências |

- ##### Tema 8: Avaliações

---
## TEMA 1: INTRODUÇÃO
### > Vídeo introdutório <

#### Dicionário: 
#####  O que é uma Linguagem de alto nível?
> é uma linguagem de programação mais próxima da linguagem humana, consecutivamente mais longe da original (0 e 1)

#####  Existem casos onde a escolha do hardware fará diferença na aplicação? 
_Sim, o hardware faz diferença na aplicação. Exemplo: Computação de alto desempenho._

#### benefícios de entender este assunto:
-  programar melhor
-  especificar melhor os equipamentos
-  comprar melhor
-  ter decisões melhores
--- 
### TEMA 2: BASE COMPUTACIONAL - Desenvolvimento do computador em 4 gerações

**[Vídeo sobre a máquina de Alan turing]** (https://play.yduqs.videolib.live/player?token=4a4cf1152f95410090a7abb36d256c2a)

Alan nessa época estudava como as máquinas poderiam ser programadas de acordo com o input de entrada que era fornecido a elas.
Nesse estudo surgiu a máquina de turing, um precursor matemático do computador.

#### 4 elementos da máquina de turing:
- Uma fita infinita dividida em células que pode ser lida e escrita
- Um cabeçote capaz de ler ou escrever em uma célula da fita e mover-se para esquerda ou direita sobre a fita
- Um registrador que mantém o estado atual da máquina
- Uma função de transição que calcula, a partir do estado atual e do símbolo lido, qual o novo estado e se o cabeçote deve -se mover ou escrever na fita

Além disso, desenvolveu estudos para a formalização do que hoje chamamos “algoritmo”.

#### O que é um algoritmo? 
>  É conjunto finito de passos capaz de resolver um determinado problema.

Por isso ele é considerado o pai da ciência da computação.
Durante a segunda guerra, ele foi chamado pelo governo inglês para ajudar na quebra dos criptogramas alemães.

**O eixo, usava uma máquina eletromecânica chamada Enigma para cifrar suas mensagens.**
A equipe de turing desenvolveu uma máquina para decifrar os símbolos e ser capaz de entender o conteúdo da mensagem interceptada. Embora não fosse um computador, esta máquina foi usada como base para o surgimento do primeiro computador.


Ainda durante a segunda guerra, **Claude Elwood Shannon** trabalhava no bell labs, onde estudava sobre a comunicação entre equipamentos. seu principal artigo **“a mathematical theory of communication”** onde **introduziu o conceito de unidade mínima para guardar uma informação.**


Dígito binário = Bit (binary digit) 1bit é a unidade mínima de informação e pode ter os seguintes valores:
```
0 = false ou desligado
1 = true ou ligado
```
Com essa simples diferença, podemos representar qualquer número e de fato qualquer informação. A isso damos o nome de representação digital binária.

Shannon é conhecido pela criação do que hoje chamamos de Teoria da Informação devido a publicação deste artigo.

**[Vídeo sobre as 4 gerações de computadores]** (https://play.yduqs.videolib.live/home?token=a20278a8265d422187fd2746b3bdd854)

## 1ª geração de computadores:
### ENIAC:
![ENIAC](https://www.cnnbrasil.com.br/wp-content/uploads/sites/12/2021/06/26776_1798DEE935286D54.jpg?w=1024)
Ainda durante a Segunda Guerra Mundial, nos Estados Unidos, foi desenvolvido o primeiro computador eletrônico da história. Trata-se do **ENIAC**, feito com válvulas termiônicas, que faziam o trabalho de uma porta lógica. O problema delas era: gasto de energia alto demais, queimaram com frequência e ocupavam muito espaço.
### Vávulas termiônicas:
![VALCULAS TERMIONICAS](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e9/Elektronenroehren-auswahl.jpg/400px-Elektronenroehren-auswahl.jpg)

## 2ª geração de computadores:

### Válvulas termiônicas para transistores: ![TRANSISTORES](https://media.licdn.com/dms/image/C4E12AQGqUss1OZVoLw/article-inline_image-shrink_400_744/0/1562562428143?e=1718841600&v=beta&t=HA6KzBGGTPjcfCAKua5lWbMY9RHYW6U3ZHRriBGQbys)

Para resolver os problemas da primeira geração, foi criado o transistor. Ele é um pequeno circuito eletrônico de apenas alguns milímetros que faz o papel da porta lógica, substituindo a válvula termiônica. Por conta do seu tamanho, também foi resolvida a questão da energia.

## 3ª geração de computadores:
![Printed Circuit Board (PCB) ouPlacas de Circuito Impresso (PCI).](https://i0.wp.com/www.orientdisplay.com/wp-content/uploads/2021/07/type6.jpg?resize=300%2C223&ssl=1)

 Printed Circuit Board (PCB), mas no Brasil, é conhecida como Placas de Circuito Impresso (PCI). é um substrato isolante, geralmente composto de fibra de vidro ou resina epóxi, que abriga uma intrincada rede de trilhas condutoras de cobre.
 
 Circuito impresso: é uma pequena pastilha de silício, que contém dentro dela uma grande quantidade de portas lógicas. Por isso, conseguimos diminuir ainda mais o tamanho do computador, sendo capazes agora de criar computadores pessoais. Que surgiram no final da década de 70, começo da década de 80.

## 4ª geração de computadores:
![Microprocessadores](https://tiagopguedes.files.wordpress.com/2014/11/transferir.jpg)

O surgimento dos microprocessadores, tem um processador inteiro em apenas um chip, minimizando ainda mais o computador, podendo embarcar em diversos dispositivos hoje em dia, como a televisão celular, aviões, enfim.

A década de 1980 presenciou a proliferação de PCs cada vez mais potentes, baratos e conectados por meio do surgimento das redes locais de computadores e da internet: a rede mundial.

Além disso, um novo equipamento aparecia nos lares: o videogame, um tipo de computador especializado, cujos programas são jogos eletrônicos com ênfase nos gráficos e na interação com os usuários.
![videogame](https://stecine.azureedge.net/repositorio/00212ti/00403/img/img-06.jpg)

## fim do séculos XX
Os computadores já eram tão pequenos e potentes que se encontravam embarcados em diversos equipamentos cotidianos, como automóveis, aviões e videogames, além de se tornar mais comum a presença dos laptops (microcomputadores pessoais portáteis) nas casas das pessoas. Não tardou muito para que eles fossem integrados a televisões e celulares. 
## 2010 pra frente
Essa integração passou a ser feita por intermédio de smartphones e smart TVs.
![smarthphoness e smartTVS](https://noticiasdatv.uol.com.br/media/uploads/noticias/2014/android_tv_com_celular1.jpg)

--- 
## TEMA 2: BASE COMPUTACIONAL - Computação no cotidiano

Hoje em dia, muitos celulares já são, de fato, computadores pessoais portáteis, plenamente conectados pela rede de telefonia móvel (celular). Nossa dependência em relação a eles para as tarefas do cotidiano já é tão forte que nem percebemos quando os utilizamos, inclusive estranhando sua ausência.

Afinal, usamos computadores para:

- Comunicação;
- Meios de transporte;
- Transações bancárias e comerciais.

Atualmente, até o dinheiro não é guardado mais em cofres. Os saldos bancários são armazenados digitalmente nos servidores dos bancos. **Se todos os correntistas de um banco solicitassem retirar inteiramente o dinheiro guardado nele, não haveria cédulas suficientes no cofre para atendê-los.**
![dinheiro](https://img.freepik.com/vetores-premium/transferir-dinheiro-online-ilustracao-de-pagamento-movel-transacao-por-telefone-pagamento-via-internet-comercial-e-banco-digital-na-mao_121223-1194.jpg)

### Saiba mais

Para demonstrar a evolução desse conceito, foi desenvolvido um sistema de troca de dinheiro independente dos bancos. Proposto em 2008, o coin utiliza uma cadeia de transações descentralizada que qualquer pessoa pode auditar: o blockchain. Com essa tecnologia, é possível receber e enviar dinheiro sem precisar de bancos, além de todas as suas transações serem verificáveis por qualquer pessoa com acesso à internet.
![blockchain](https://www.researchgate.net/publication/368740478/figure/fig4/AS:11431281122017345@1677165755482/Figura-4-Explicando-o-blockchain.jpg)

---

## TEMA 2: BASE COMPUTACIONAL - Tendências

O ramo da Ciência da Computação está em amplo desenvolvimento. Segundo o portal Statista, em 2019, cinco das seis maiores companhias do mundo (em valor de mercado) eram do ramo da computação:

- apple;
- microsoft;
- amazon;
- google;
- faebook;

Na área da tecnologia, estudos e pesquisas continuam sendo realizados em busca de um novo salto de desenvolvimento.

Exemplo
Computadores quânticos usam as características da mecânica quântica a fim de permitir a solução de problemas muito complexos para PCs convencionais.

matéria exemplificando: [google e computação quântica](https://www.rtp.pt/noticias/mundo/computador-quantico-resolve-em-tres-minutos-equacao-para-10-mil-anos_n1181111)

### Superposição:
Sem ir muito longe nas definições do que é um computador quântico, é possível dizer que o segredo de sua grande capacidade de processamento vem da superposição. Trata-se de um fenômeno da física quântica que permite que partículas assumam múltiplos estados simultaneamente. É isso que permite que um computador quântico analise bilhões de possibilidades ao mesmo tempo.

#### trocando em miúdos 

Imagine que você está em uma sala com duas portas. Você pode escolher entrar em uma porta ou na outra. Agora, imagine que você é uma partícula quântica. Em vez de escolher uma porta de cada vez, você pode entrar nas duas portas ao mesmo tempo! Isso é superposição.

Então, quando falamos sobre um computador quântico, ele pode fazer muitas coisas ao mesmo tempo, como analisar bilhões de possibilidades de uma só vez. Isso é porque as "portas" que ele usa (chamadas de "qubits") podem estar em múltiplos estados ao mesmo tempo, graças à superposição. Isso torna os computadores quânticos muito poderosos para resolver certos tipos de problemas.

--- 

# Hora de praticar os conhecimentos

### Questão 1
Potentes, os computadores atuais podem ser levados até nossos bolsos, como é o caso dos celulares. Entretanto, em sua primeira versão, um computador ocupava uma sala inteira e pesava o equivalente a 30 carros. Para essa enorme evolução acontecer, diversas descobertas científicas e tecnológicas foram fundamentais.

Assinale a alternativa que contém o conjunto de tecnologias desenvolvido na ordem cronológica correta para permitir o desenvolvimento dos computadores:

a) Transistor, microprocessador e circuito integrado.
b) Rádio, válvulas termiônicas e microprocessador.

- c) Transistor, circuito integrado e microprocessador.

d) Transistor, circuito integrado e rádio.
e) Transistor, microprocessadores e válvulas termiônicas

### Questão 2
Assim como a maioria dos avanços tecnológicos, os computadores foram construídos e desenvolvidos a partir de outras tecnologias que os precederam. Assinale a alternativa que **não** representa uma tecnologia precursora dos computadores:

a) Máquina universal de Turing
- b) Transistor (O primeiro computador funcionava à base de válvulas termiônicas. O transistor as substituiu posteriormente.)

c) Calculadora
d) Energia elétrica
e) Abacos
---

## TEMA 2: BASE COMPUTACIONAL - Hardware & Software

Os computadores são feitos com um conjunto de componentes dividido em dois grandes grupos:

### Hardware (HW)
> Componentes físicos, ou seja, o que pode ser visto e tocado.
### Software (SW)
> Programas executados no computador.


Apresentaremos, a seguir, os diversos tipos de hardware presentes em um computador e os tipos de software mais importantes. Além disso, entenderemos como a interação entre eles permite que nossos PCs sejam capazes de resolver quase todos os problemas, abrindo o caminho para soluções inovadoras e não planejadas.

### Conceitos

A grande propagação dos computadores se deve à implementação de diversas funções genéricas (hardware) e ao uso delas para gerar programas úteis a muitas pessoas (software). O hardware forma a base para o que conseguimos extrair de um sistema computacional.

### Exemplo
Se você tentar se conectar à internet em um computador sem placa de rede, não conseguirá. Isso se deve à falta do hardware, que é o responsável por dar uma capacidade de conexão à internet: a placa de rede.