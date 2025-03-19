# Referencial Teórico

## 1. Componentes de Hardware

### 1.1 CPU (Unidade Central de Processamento)

Uma unidade central de processamento (CPU) é um componente de hardware que é a unidade computacional principal em um servidor. Servidores e outros dispositivos inteligentes convertem dados em sinais digitais e executam operações matemáticas neles. A CPU é o principal componente que processa os sinais e torna a computação possível. Ela atua como o cérebro de qualquer dispositivo de computação. Ela busca instruções na memória, executa as tarefas necessárias e envia a saída de volta para a memória.

### Diferenças entre Processadores Intel e AMD

Intel e AMD são duas das maiores fabricantes de processadores para computadores, e ambas oferecem produtos competitivos, mas com diferenças significativas em termos de arquitetura, desempenho, eficiência energética e preço. Aqui estão algumas das principais diferenças entre os processadores Intel e AMD:

### 1.1 Arquitetura e Tecnologia

- **Intel**: Utiliza arquiteturas como a "Core" (ex.: Core i3, i5, i7, i9) e recentemente introduziu a arquitetura híbrida com os processadores da 12ª geração (Alder Lake) e posteriores, combinando núcleos de desempenho (Performance Cores) e núcleos eficientes (Efficient Cores).
- **AMD**: Utiliza a arquitetura "Zen", que evoluiu para Zen 2, Zen 3 e Zen 4. A AMD também introduziu a tecnologia de chiplets, onde diferentes partes do processador são fabricadas separadamente e depois integradas, o que pode reduzir custos e melhorar a eficiência.

### 1.2 Desempenho

- **Intel**: Tradicionalmente, os processadores Intel têm sido conhecidos por seu forte desempenho single-thread (mononúcleo), o que é importante para aplicações que não são bem otimizadas para múltiplos núcleos, como alguns jogos e software mais antigo.
- **AMD**: Com a arquitetura Zen, a AMD tem se destacado no desempenho multi-thread (multinúcleo), o que é benéfico para tarefas que podem ser divididas em vários núcleos, como renderização de vídeo, modelagem 3D e multitarefa pesada.

### 1.3 Eficiência Energética

- **Intel**: Processadores Intel tendem a consumir mais energia, especialmente em modelos de alta performance, o que pode resultar em maior geração de calor e necessidade de sistemas de refrigeração mais robustos.
- **AMD**: Com a arquitetura Zen, a AMD tem se mostrado mais eficiente em termos de consumo de energia, especialmente com a introdução do processo de fabricação de 7nm, o que resulta em menor consumo de energia e menor geração de calor.

### 1.4 Preço

- **Intel**: Geralmente, os processadores Intel tendem a ser mais caros, especialmente os modelos de alta performance.
- **AMD**: A AMD frequentemente oferece uma relação custo-benefício mais atraente, com processadores que oferecem desempenho comparável ou superior a preços mais baixos.

### 1.5 Integração de Gráficos

- **Intel**: Muitos processadores Intel vêm com gráficos integrados (Intel UHD Graphics ou Iris Xe), o que pode ser uma vantagem para usuários que não precisam de uma placa de vídeo dedicada.
- **AMD**: A AMD também oferece processadores com gráficos integrados (APUs), como as séries Ryzen com gráficos Vega ou RDNA, que geralmente oferecem desempenho gráfico superior em comparação com as soluções integradas da Intel.

### 1.6 Compatibilidade e Atualização

- **Intel**: A Intel frequentemente muda os soquetes (sockets) com novas gerações de processadores, o que pode limitar a capacidade de atualização sem a necessidade de trocar a placa-mãe.
- **AMD**: A AMD tem mantido uma política mais consistente com a compatibilidade de soquetes, especialmente com o AM4, que suportou várias gerações de processadores, facilitando a atualização.

### 1.7 Overclocking

- **Intel**: A Intel permite overclocking apenas em processadores com a letra "K" no nome (ex.: Core i7-12700K) e em placas-mãe com chipset Z ou X.
- **AMD**: A AMD permite overclocking na maioria de seus processadores Ryzen, e muitos chipsets AMD suportam overclocking, oferecendo mais flexibilidade para entusiastas.

### 1.8 Mercado e Segmentação

- **Intel**: Tem uma forte presença em mercados corporativos e em laptops, com uma ampla gama de opções para diferentes segmentos.
- **AMD**: Tem ganhado participação de mercado significativa, especialmente em desktops e servidores, com processadores Ryzen e EPYC, respectivamente.

### Comparativo: Ryzen 5 5600X vs Intel Core i5-11400F

| Característica          | Ryzen 5 5600X (AMD)        | Intel Core i5-11400F   |
| ----------------------- | -------------------------- | ---------------------- |
| **Núcleos/Threads**     | 6 núcleos / 12 threads     | 6 núcleos / 12 threads |
| **Clock Base/Boost**    | 3,7 GHz / 4,6 GHz          | 2,6 GHz / 4,4 GHz      |
| **Arquitetura**         | Zen 3 (7nm)                | Rocket Lake (14nm)     |
| **TDP**                 | 65W                        | 65W                    |
| **Grágicos Integrados** | Não                        | Não                    |
| **PCIe**                | PCIe 4.0                   | PCIe 4.0               |
| **Cache L3**            | 32 MB                      | 12 MB                  |
| **Overclocking**        | Desbloqueado (suporta PBO) | Não desbloqueado       |
| **Preço (lançamento)**  | Mais caro                  | Mais barato            |

### Desempenho Single-Core:

- **Ryzen 5 5600X:** Superior, graças à arquitetura Zen 3 e clocks mais altos.
- **Intel Core i5-11400F:** Bom, mas ligeiramente inferior ao Ryzen 5 5600X.

### Desempenho Multi-Core:

- **Ryzen 5 5600X:** Melhor, devido ao cache L3 maior (32 MB) e maior eficiência.
- **Intel Core i5-11400F:** Competitivo, mas limitado pelo cache L3 menor (12 MB).

### Eficiência Energética:

- **Ryzen 5 5600X:** Mais eficiente, por ser fabricado em 7nm.
- **Intel Core i5-11400F:** Menos eficiente, por ser fabricado em 14nm.

### Overclocking:

- **Ryzen 5 5600X:** Suporta overclocking (PBO).
- **Intel Core i5-11400F:** Não suporta overclocking.

### Preço:

- **Ryzen 5 5600X:** Mais barato - R$969,99
- **Intel Core i5-11400F:** Mais caro - R$1069,00
  (19/03/2025)

## 2. GPU (Unidade de Processamento Gráfico)

A **GPU** (Unidade de Processamento Gráfico) é um componente de hardware responsável por processar e renderizar imagens, vídeos e gráficos. Ela também é conhecida como **placa de vídeo**. A GPU funciona recebendo dados brutos (números, comandos, texturas) e transforma tudo isso nas imagens que aparecem na tela.

### Diferenças entre GPUs NVIDIA e AMD

#### **NVIDIA:**

- O **Ray Tracing** emerge como um dos principais diferenciais, permitindo renderizações extremamente realistas ao simular o comportamento da luz em tempo real.
- Essa tecnologia alcançou um novo patamar com as GPUs **RTX**, que contam com núcleos específicos para o processamento de ray tracing, superando as implementações da AMD em precisão e desempenho.

#### **AMD:**

- A AMD aposta em soluções que otimizam a comunicação entre a CPU e a GPU quando os componentes pertencem à marca, resultando em ganhos de desempenho significativos.
- O **Infinity Cache** (tecnologia de cache da AMD) amplia significativamente a largura de banda, reduzindo gargalos e aumentando a eficiência em jogos com resoluções mais altas.

### Modelos Populares

#### **NVIDIA GeForce GTX 1650:**

- A GeForce GTX 1650 é uma placa de vídeo de entrada muito popular da NVIDIA, ideal para quem quer uma boa experiência em jogos sem precisar gastar muito.

#### **AMD Radeon RX 6600:**

- A Radeon RX 6600 é uma das opções mais acessíveis da AMD, pensada para gamers que desejam jogar em **1080p** com um orçamento limitado.

### Impacto da GPU em Jogos e Renderização Gráfica

As GPUs são muito importantes nos jogos, garantindo que:

- Os gráficos sejam de alta qualidade;
- Os movimentos sejam fluidos;
- Os efeitos visuais sejam impressionantes.

O poder de processamento das GPUs modernas é essencial para criar experiências imersivas e realistas para os jogadores.

## 3. Memória RAM(Memória de Acesso Aleatório)

A memória RAM (Random Access Memory) é um componente essencial em computadores e dispositivos móveis, responsável por armazenar temporariamente dados e instruções que o processador necessita para executar tarefas de forma rápida e eficiente. Diferente de dispositivos de armazenamento permanentes, como HDs ou SSDs, a RAM é volátil, ou seja, seus dados são perdidos quando o aparelho é desligado.
Existem diferentes tipos de RAM, sendo os mais comuns atualmente o DDR4 e o DDR5. O DDR4, amplamente utilizado, oferece frequências que variam de 2133MHz a 4800MHz e além, proporcionando um equilíbrio entre desempenho e eficiência energética. Já o DDR5, mais recente, traz melhorias significativas, como maior largura de banda, eficiência de canais aprimorada e melhor gerenciamento de energia, permitindo sistemas de computação multi-core de última geração.

A quantidade ideal de RAM varia conforme o uso do sistema. Para tarefas básicas, como navegação na internet e uso de aplicativos de escritório, 8GB geralmente são suficientes. Para atividades mais intensivas, como edição de vídeo, design gráfico e jogos modernos, 16GB ou mais são recomendados para garantir um desempenho fluido e evitar gargalos.
A RAM desempenha um papel crucial no desempenho multitarefa, permitindo que o computador execute muitas tarefas diárias, como carregar aplicativos, navegar na internet e editar planilhas. Ela também permite alternar rapidamente entre essas tarefas, lembrando onde você está em cada uma. De forma geral, quanto mais memória você tiver, melhor será a capacidade de realizar multitarefas simultaneamente.

### 4. Armazenamento

### 4.1 Diferenças entre SSD e HD

Na hora de escolher os componentes de um computador, uma das principais dúvidas é sobre o tipo de armazenamento: SSD ou HD? Ambos têm a mesma função de armazenar dados, mas possuem funcionamentos e desempenhos diferentes, o que pode impactar no desempenho geral da máquina.

### 4.2 O que é o HD?

Os HDs são dispositivos de armazenamento mais tradicionais, que possuem pratos giratórios para ler e gravar dados. Funcionam de forma mecânica, utilizando discos giratórios e um cabeçote móvel de leitura/gravação. A principal vantagem dos HDs é a grande capacidade de armazenamento e o preço mais acessível por gigabyte.

#### 4.3 Vantagens do HD:

- Capacidade elevada (1TB, 2TB ou mais);
- Preço mais baixo;
- Ideal para armazenar grandes volumes de arquivos, como vídeos, fotos e documentos.

#### 4.4 Desvantagens do HD:

- Mais lento na leitura e gravação de dados;
- Mais vulnerável a danos físicos por ter peças móveis;
- Consome mais energia e esquenta mais.

### 4.5 O que é o SSD?

Os SSDs são tipos de armazenamento mais recentes que não possuem partes móveis. Eles funcionam armazenando dados em chips de memória flash, o que os torna muito mais rápidos e resistentes a impactos.

#### 4.6 Vantagens do SSD:

- Inicialização do sistema e abertura de programas mais rapidamente;
- Velocidade de leitura e gravação muito superior;
- Mais resistente a quedas e impactos;
- Consumo de energia reduzido.

#### 4.7 Desvantagens do SSD:

- Custo por gigabyte mais alto;
- Capacidade de espaço, no geral, inferior em comparação com o HD.

### 5. Placa-Mãe

A **placa-mãe** é a principal placa de circuito impresso de um computador, atuando como a espinha dorsal que conecta e permite a comunicação entre todos os componentes do sistema. Ela hospeda o processador (CPU), memórias (RAM), unidades de armazenamento, placas de vídeo (GPU) e outros periféricos, garantindo que todos trabalhem em conjunto de forma harmoniosa.

Para que essa comunicação entre os componentes aconteça de maneira eficiente, a placa-mãe utiliza **barramentos**. O **barramento** é um conjunto de linhas de comunicação que permite a transferência de dados entre diferentes partes do sistema. Ele funciona como uma espécie de "autoestrada" por onde os dados trafegam dentro do computador, conectando a CPU, memória, dispositivos de entrada e saída, entre outros.

#### 5.1 Tipos de Barramento:

1. **Barramento de Dados:**

   - Responsável por transportar as informações que serão processadas pela CPU.

2. **Barramento de Endereço:**

   - Utilizado para indicar a localização dos dados na memória.

3. **Barramento de Controle:**
   - Responsável por coordenar e controlar o fluxo de dados dentro do sistema.

A eficiência e a velocidade dos barramentos influenciam diretamente o desempenho geral do computador, pois determinam a rapidez com que os dados são transferidos entre os componentes. Portanto, tanto a placa-mãe quanto os barramentos desempenham papéis fundamentais para garantir que o sistema funcione de maneira rápida e eficiente.

### 5.2 Compatibilidade com outros componentes (CPU, RAM, GPU)

A compatibilidade entre a placa-mãe e os componentes é essencial para o funcionamento adequado do computador:

#### 5.2.1 **CPU:**

- Cada placa-mãe possui um **soquete específico** que acomoda apenas determinados modelos de processadores. Por exemplo, processadores Intel e AMD utilizam soquetes diferentes.
- Além disso, o **chipset** da placa-mãe deve ser compatível com a geração e o modelo do processador escolhido.

#### 5.2.2 **RAM:**

- As placas-mãe suportam tipos específicos de memória RAM, como **DDR3**, **DDR4** ou **DDR5**.
- Possuem limitações quanto à **capacidade máxima** e à **frequência suportada**. É crucial verificar essas especificações para garantir compatibilidade e desempenho ideais.

#### 5.2.3 **GPU:**

- A maioria das placas de vídeo modernas utilizam o slot **PCI Express (PCIe)** para conexão.
- É importante certificar-se de que a placa-mãe possui slots PCIe adequados e que a **fonte de alimentação** fornece energia suficiente para a GPU escolhida.
