# 🔌 Glossário de Componentes Eletrônicos - Kit Arduino

Este repositório contém o código-fonte de um site estático desenvolvido como parte da disciplina de **PAC Extensionista** no curso de **Pedro Martins do Nascimento**. O projeto funciona como um guia de referência rápido e visual para os principais componentes de um kit de eletrônica baseado em Arduino.

## 🎯 Objetivos de Aprendizagem

O principal objetivo foi criar um guia de referência claro e acessível que pudesse ser utilizado por outros estudantes. Durante o desenvolvimento, os focos de aprendizagem foram:

-   **Praticar HTML5 semântico:** Utilizar as tags corretas para cada tipo de conteúdo, garantindo a acessibilidade e a estrutura lógica do documento.
-   **Exercitar clareza e padronização:** Criar uma documentação técnica limpa, organizada e consistente.
-   **Consolidar conceitos de eletrônica:** Documentar informações essenciais como nome, uso, pinagem e valores dos componentes.
-   **Publicar um material reutilizável:** Disponibilizar um recurso que possa servir como fonte de consulta para outros colegas.

## 💻 Tecnologias Utilizadas

Este projeto foi construído do zero, focando nos fundamentos do desenvolvimento web e cumprindo o requisito de não ter dependências externas (bibliotecas ou frameworks).

-   **HTML5**
-   **CSS3**

## 📂 Estrutura do Site

O site foi desenvolvido seguindo a abordagem de **página de índice com âncoras para uma página de conteúdo**, conforme uma das opções da atividade. A estrutura de arquivos é a seguinte:

```
/
├── index.html # Página inicial com a grade de links para os componentes.
├── componentes.html # Página única contendo os "cards" de todos os componentes, com IDs para as âncoras.
├── style.css # Arquivo de estilos para todo o site.
└── assets/ # Pasta para armazenar as imagens dos componentes.
```

## 📜 Componentes Documentados

O glossário inclui a documentação para os seguintes componentes:

-   **Microcontrolador:** BlackBoard UNO R3
-   **Atuadores:** Micro Servo Motor, Garra ANT, Buzzer, Mini Laser
-   **Entradas / Controles:** Módulo JoyStick, Chaves Momentâneas (Botões), Potenciômetro
-   **Sensores:** Sensor Ultrassônico, Sensor de Temperatura e Umidade, LDR 5mm (Sensor de Luminosidade)
-   **Saídas Visuais (Displays e LEDs):**
    -   Display de 7 Segmentos
    -   LED Vermelho
    -   LED Amarelo
    -   LED Verde
    -   LED RGB
    -   LED Alto Brilho
-   **Componentes de Circuito:**
    -   Protoboard de 400 Pontos
    -   Jumpers M/M (Macho/Macho)
    -   Jumpers M/F (Macho/Fêmea)
    -   Resistor 300 ohm
    -   Resistor 10K ohm
    -   CI 4511 (Decodificador para Display)
-   **Acessórios e Ferramentas:** Workplate 400, Cabo USB, Chave Philips


## 🚀 Como Visualizar

O site está disponível para visualização através do GitHub Pages no seguinte link:

**https://pedro-martins-nascimento.github.io/Arduino/**


Alternativamente, você pode clonar este repositório e abrir o arquivo `index.html` diretamente em seu navegador.

```bash
git clone https://github.com/Pedro-Martins-Nascimento/Arduino.git
cd Arduino
# Abra o arquivo index.html no navegador
