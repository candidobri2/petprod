---
title: "Blockchain e seu lugar na Indústria 4.0"
date: 2021-12-15T18:19:00+06:00
author: "Edgar Queiroz"
image: "images/blog/block1.jpg"
summary: "A Indústria 4.0 é um dos temas mais discutidos atualmente nas Engenharias, por sua capacidade de conseguirmos estudá-la antes mesmo de vê-la sendo uma realidade para a maior parte das indústrias. Temos diversas tecnologias que prometem ser uma revolução para essa indústria do conhecimento, e neste artigo, gostaríamos de descomplicar uma delas para você!"
type: post_blog
draft: false

---
A Indústria 4.0 é um dos temas mais discutidos atualmente nas Engenharias, por sua capacidade de conseguirmos estudá-la antes mesmo de vê-la sendo uma realidade para a maior parte das indústrias. Temos diversas tecnologias que prometem ser uma revolução para essa indústria do conhecimento, e neste artigo, gostaríamos de descomplicar uma delas para você!

### O que é uma Blockchain?

Você já deve ter ouvido falar do termo “Blockchain”, seja na consulta de um investimento financeiro, no noticiário ou alheio pela internet. Diversas vezes o termo é referenciado em conjunto às criptomoedas, pois muitas operam com a Blockchain. O maior exemplo de uma criptomoeda que opera com base na Blockchain é o Bitcoin, a criptomoeda mais popular do momento. Não podemos dissociar da Blockchain, entretanto, a importância do Bitcoin para o seu desenvolvimento, que foi apenas a partir do desenvolvimento da rede de Blockchain que abriga o Bitcoin que surgiu o interesse por melhor desenvolver essa tecnologia. Mas é importante saber também que não existe apenas uma rede de Blockchain, quando falamos anteriormente, estávamos nos referindo especificamente à rede que abriga os Bitcoins.

Para aprofundarmo-nos neste artigo, temos que quebrar esse preceito de que a Blockchain existe apenas para abrigar criptomoedas, pois pode ser muito difícil conseguir achar bom conteúdo sobre este tema sem ter que filtrar múltiplas páginas que falam apenas de criptomoedas. Você sabia que essa tecnologia não passa de um tipo de “base de dados”? Seu conceito pode parecer complicado para muitos, mas na prática é simples! Você mesmo pode rodar um ponto, ou também chamado “nó”, de blockchain na sua casa se tiver uma máquina capaz, e com isso também será possível observar o quanto essa tecnologia irá revolucionar o trânsito de dados internacionais. Não existe apenas uma blockchain, todos podem criar sua própria blockchain com sua função de hash, ou hospedar pontos de comunicação para blockchains existentes.

{{< figure src="/images/blog/block2.png#center" height="auto" width="auto" description="" >}}

A priori, entendemos blockchain, de fato, como uma cadeia de blocos, trazendo uma tradução literal do inglês. Estes blocos são os responsáveis por armazenar os dados que inserimos neles, além disso, uma propriedade desses blocos, é que os dados armazenados são incrivelmente difíceis de serem adulterados, tornando a blockchain um sistema de troca de informações bem seguro. A seguir vemos as principais partes dos blocos:

• Dados: De fato, a parte principal de um bloco. Se analisarmos o caso dos Bitcoins, ao realizarmos um pagamento, os dados que são transferidos por meio da blockchain são os dados do *remetente*, *destinatário*, e o *valor* da transação. <br/>

• Hash: Pode ser considerado a parte da “segurança” do bloco, muitas vezes é considerado como uma assinatura eletrônica, e cada bloco possui uma assinatura única. O tipo de hash depende da blockchain em uso, no caso dos bitcoins, o Hash utilizado é a função SHA-256. Outra coisa que vale notar; quando você consegue mudar algum dado dentro de um bloco, seu hash muda completamente. <br/>

• Hash do Bloco Prévio: Há a necessidade, para as blockchains, de termos um bloco “primordial”, ou seja, o primeiro bloco que gerou a cadeia de blockchain. Chamamos o primeiro bloco de "genesis block”, ou bloco gênese, seguindo uma sequência, cada novo bloco é gerado a partir de um bloco já existente. Por isso foi importante mencionar que caso algum dado mudar dentro de um bloco, temos que sua hash muda completamente, então caso tivermos uma relação entre dois blocos, que o valor de “hash” do bloco prévio a ele não bater, temos o alerta de que os dados dentro daquela blockchain foram adulterados. <br/>


### Como funcionam as Blockchains?

Beleza, aí tem outra pergunta: quem verifica de fato a legitimidade dos blocos? Lembra quando falamos que você mesmo pode rodar um “nó”, ou “node”, de blockchain na sua casa? Isso se dá por conta que a Blockchain é uma tecnologia que opera Peer-to-Peer (P2P), ou seja, de máquina para máquina. Você, ao hospedar um pedaço da sua blockchain em casa, está contribuindo diretamente para que ela funcione cada vez melhor para todos os conectados. Quando novos blocos são inseridos em uma blockchain, elas têm que passar por uma verificação, que é realizada por máquinas que realizam a mineração de dados a fim de encontrar, por exemplo, inconsistências ocasionais no bloco. A seguir, alguns dos tipos mais famosos de verificação destes dados na blockchain:

{{< figure src="/images/blog/block3.png#center" height="1024" width="970" description="" >}}

• Proof of Work (PoW): Popularizado pelo Bitcoin. Ao adicionar um novo bloco à blockchain, todos os “nós” conectados naquela cadeia de blocos trabalham para tentar inserir aquele bloco na rede. Para isso, eles têm de gerar um hash para aquele bloco, caso ele seja verificado como legítimo. Dependendo de quantos “nós”, ou nesse caso, mineradores estão conectados, mais difícil fica a geração desse hash, pois o computador demanda cálculos cada vez mais pesados. Para o Bitcoin, no momento em que todos os Bitcoins foram minerados, o aumento do número de pessoas contribuindo com “nós” para a Blockchain irá resultar em impactos positivos para o tempo de espera das transações, e em taxas menores para quem realiza elas. <br/>

• Proof of Stake (PoS): Este é mais recente, e será adotado por outra criptomoeda famosa, a Ethereum, e também apenas existem exemplos com aplicação em criptomoedas. O PoW é um método que requer um gasto energético muito alto, e para isso, consome muitos recursos energéticos e é ruim sob um viés sustentável, além de ser ineficiente em relação a velocidade e taxas. A maneira como o PoS funciona para a validação de transações, é a partir da participação dos validadores em relação à moeda. Ou seja, quem possui mais criptomoedas está escalado para validar estes blocos novos. A partir disso, não temos um gasto energético tão alto com a mineração de dados, pois os hashes não se tornam mais difíceis de serem gerados, além de uma maior agilidade com o tempo de transação e menos taxas para as pessoas. Porém, há discussões que o PoS pode ser menos seguro que o PoW, pois em um cenário em que uma pessoa pelo menos 50% de todas as moedas (cenário altamente improvável), ela terá praticamente todo o poder de validação da blockchain consigo. <br/>

Ainda falando sobre Ethereum, poderíamos citar os “Smart Contracts”, ou contratos inteligentes, que foram primeiro citados em 1997 com a ideia de trazer para o mundo digital alguma coisa similar aos contratos burocráticos. Também são colocados dentro da blockchain, mas ao invés de dados, temos pequenos programas de computador que são depositados em blocos. 

A pegada dos Smart Contracts são a sua finalidade, falando da Ethereum como o principal exemplo, qualquer um pode gerar um Smart Contract com alguma finalidade, caso seja validado, e operações de dados/financeiras podem ser realizadas através dela, sem necessidade da intervenção de terceiros. Pode ter ficado um pouco confuso ainda, não é? Vamos tomar o exemplo de uma casa de câmbio. Caso você queira viajar, terá de transformar seu dinheiro, em real (R$) por exemplo, para dólares (USD), caso viaje para os Estados Unidos, mas para fazer isso, terá de passar por uma casa de câmbio, ou seja, um serviço terceirizado, que pode adotar diferentes taxas de conversão dependendo de onde você vá. 

{{< figure src="/images/blog/block4.png#center" height="450" width="800" description="" >}}

Os Smart Contracts estão aqui para eliminar isso, fazendo com que todos os acordos sejam imutáveis, ou seja, não tem como você mudar uma ordem de câmbio com intuitos maliciosos, e em casos de contratos que envolvam mais pessoas, é muito fácil de realizar um retorno para elas caso alguns critérios não sejam atendidos. Apenas dei exemplos com relação à criptomoedas, pois estes são os mais proeminentes na atualidade, mas as perspectivas para essas tecnologias são inúmeras: Desde a implementação de uma logística mais inteligente, com pagamentos que são realizados apenas com a finalização das tarefas, validação de seguros, gestão de cadeias de suprimentos, e entre muitas outras coisas.

Outra curiosidade, falei que ao invés de dados, os Smart Contracts são programas que são depositados nos blocos, estes podem ser escritos com as mais diversas linguagens de programação dependendo da blockchain, mas no caso da Ethereum, a mais famosa, temos Smart Contracts sendo escritos com uma linguagem chamada “Solidity”.

### E a Indústria 4.0? Como se beneficia disso?

Ótima pergunta! Afinal, este era o propósito deste artigo. Com a insurgência da Indústria 4.0, que engloba os meios físicos, digitais e biológicos, no que chamamos de meio ciber físico, é notório que precisamos nos comunicar para transmitir as informações desejadas. Da mesma forma que é possível interceptar a conversa de duas pessoas com muita facilidade, isso também pode ser aplicado no contexto de dados que estão em trânsito constantemente, necessitando de uma maior segurança e agilidade para o processo.

Com o advento da “Internet of Things” (IoT) e o acúmulo de dados proveniente de uma cada vez maior inclusão digital, no que podemos chamar de “Big Data”, torna-se um desafio cada vez maior de tratar, transmitir e proteger esses dados. A Blockchain não foi desenvolvida como uma solução para isso, mas desenvolveu-se a ponto de ser uma das tecnologias mais visadas para a solução desse problema moderno. Lei Hang e Do-Hyeun Kim desenvolveram um artigo em 2019 que elaborava um modelo para a implementação da blockchain em indústrias, que pode ser ilustrada a seguir:

{{< figure src="/images/blog/block5.png#center" height="auto" width="auto" description="" >}}

Na figura, temos diversos dispositivo locais armazenando dados pertinentes à produção, denominados aqui de “Local Bridges”, estes podem estar dispostos em diferentes fábricas ao redor do mundo, e todos eles operam alimentando informações para uma plataforma de blockchain central, acima denominado como “IoT Server”. A beleza da coisa é a possibilidade de integrar toda uma cadeia mundial de suprimentos, com dados estratégicos sobre produção e tudo mais, de forma segura e praticamente instantânea.

Outro ponto bastante positivo sobre a tecnologia de Blockchain, é que a grande maioria de suas ferramentas são de código-aberto, ou seja, caso haja interesse de adoção de uma tecnologia blockchain, é possível utilizar um programa já desenvolvido, ou adequá-lo para suas necessidades por meio de manipulação do código-fonte, e também analisar possíveis falhas de segurança no código.

Um exemplo de plataforma de código-aberto, já amplamente estabelecida nesse contexto, é a Hyperledger Fabric, que foi projetada para o ambiente empresarial, que opera baseada nos “Smart Contracts” citados acima em uma rede de blockchain privada.

Blockchains possuem duas subdivisões em relação à privacidade, que podem ser definidas principalmente como:

• Públicas: Não requer prévia verificação para criar seu próprio “nó”, é o tipo utilizado nas criptomoedas em sua maioria, Bitcoin como exemplo. <br/>

• Privadas: Precisa-se de verificação para poder ser inserido na rede para a verificação de novos blocos. Ideal para o ambiente empresarial e é o conceito utilizado na Hyperledger Fabric. <br/>

Finalizando, em um contexto cada vez crescente também do uso da Inteligência Artificial, o uso de Blockchains para a integração de redes multinacionais de dados é imprescindível, pois muitas vezes já consegue tratar de cara os maiores problemas da ciência de dados, que é o pré-tratamento de dados, pois caso houver alguma incoerência nos dados a serem inseridos no banco de dados, os “nós” irão rejeitar o bloco, de forma que será necessário adequá-lo para que possa ser inserido na Blockchain.

Com isso, é possível concluir a importância da Blockchain para o contexto da integração dos meios industriais, com enfoque na necessidade para poder facilitar o trabalho dos cientistas de dados, a fim de trazer inúmeros benefícios para a empresa, como a realização de projeções em tempo real de sistemas produtivos e relatórios que podem ser atualizados com intervalos de segundos por sua vez. Pode ser difícil encontrar boa leitura sobre o tema na Internet por conta do pulo em popularidade das criptomoedas, e também dissociar o conceito de blockchain delas, mas essa tecnologia vai bem além de tudo isso.


