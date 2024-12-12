# carona-joacaba
Projeto para a matéria de Práticas Extensionistas IV na Unoesce Joaçaba - Carona Unoesc Joaçaba

Professor: Roberson Junior Fernandes Alves

Curso: Análise e desenvolvimento de Sistemas (Joaçaba)

Alunos: Vagner Lucas Gomes - 114256
      Amanda Ximendes de Lima - 426628


-------
#### [Documentaçao](doc/Projeto%20carona%20joaçaba.drawio%20(1).pdf)

#### [implementação backend] (https://github.com/vaglucas/carona_unoesc)
#### [implementação app] (https://github.com/vaglucas/app_carona)
--------

## Infra:

* a infra escolhida para implantar a aplicação foi a GCP;
    * Motivos: Disponibilidade, custos, documentação, inteface amigavel, comunidade.

-------

## **Motivação**

A proposta desta aplicação é enfrentar um problema recorrente entre os estudantes de Joaçaba que se deslocam para a universidade: o grande número de veículos nas ruas em horários de pico. Isso não apenas causa congestionamentos, mas também aumenta a emissão de poluentes e eleva os custos para os estudantes que precisam usar transporte próprio ou alternativo. A solução proposta busca:

- **Reduzir o número de veículos no trânsito**.
- **Incentivar o compartilhamento de caronas**, proporcionando uma alternativa econômica e sustentável.
- **Diminuir a pegada ecológica**, com menos carros circulando e, portanto, menos emissão de gases poluentes.

## **Como será feito**

O desenvolvimento da aplicação envolverá uma arquitetura moderna e eficiente, utilizando tecnologias de ponta:

- **Backend:** Será desenvolvido em **Go (Golang)**, uma linguagem que oferece alta performance e escalabilidade, garantindo que a aplicação tenha uma resposta rápida e suporte um grande número de usuários simultâneos.
  
- **Frontend:** O **Flutter** será utilizado para o desenvolvimento da interface mobile, permitindo uma experiência rica e fluida, além de facilitar a compatibilidade entre as plataformas Android e iOS.
  
- **Banco de Dados:** O **MongoDB** será o sistema de banco de dados escolhido por sua flexibilidade e por ser orientado a documentos, facilitando o armazenamento e recuperação dos dados de caronas, passageiros, motoristas e custos.

- **Hospedagem:** Toda a infraestrutura será hospedada na **Google Cloud Platform (GCP)**, aproveitando a escalabilidade, segurança e integração que a plataforma oferece, garantindo que a aplicação possa crescer conforme a demanda aumenta.

## **Funcionalidades da Aplicação**

A aplicação oferecerá as seguintes funcionalidades aos seus usuários:

- **Cadastro de veículos:** Motoristas poderão cadastrar seus carros, informando capacidade, modelo e outros detalhes relevantes.
- **Cadastro de passageiros:** Estudantes poderão se registrar como passageiros, facilitando a busca por caronas.
- **Buscar caronas:** Os passageiros poderão encontrar caronas disponíveis em tempo real, buscando por horário, local de partida e destino.
- **Oferecer caronas:** Motoristas poderão oferecer vagas em seus veículos, disponibilizando horários e rotas.
- **Divisão de custos:** A aplicação também permitirá a divisão dos custos da viagem, seja combustível ou pedágios, de forma justa e organizada.

## **Resultados Esperados**

A expectativa é que a implementação desta solução gere uma série de benefícios diretos e indiretos para os estudantes e a cidade:

- **Redução nos custos de transporte**: Com o compartilhamento de caronas, os estudantes poderão dividir despesas como combustível e manutenção dos veículos, tornando o deslocamento mais acessível.
  
- **Menos veículos em circulação**: Com a adesão ao sistema de caronas, espera-se uma diminuição significativa do número de carros nas ruas durante os horários de pico, o que, além de melhorar a fluidez do trânsito, reduz a necessidade de mais investimentos em infraestrutura viária.

- **Impacto ambiental positivo**: Ao diminuir a quantidade de carros, também será possível reduzir a emissão de CO2 e outros poluentes, colaborando para um ambiente mais limpo e sustentável.

---
