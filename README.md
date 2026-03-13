# Metodologia DevOps
---

# 1. Definição

O DevOps é uma abordagem que combina **práticas, ferramentas e uma cultura organizacional colaborativa** com o objetivo de integrar as equipes de desenvolvimento de software e operações de TI. Essa integração permite que as empresas **desenvolvam, testem e distribuam aplicações e serviços de forma mais rápida, eficiente e confiável**.

DevOps é uma junção das palavras inglesas **Development (desenvolvimento)** e **Operations (operações)**. Trata-se de uma abordagem cultural e técnica que une as equipes de desenvolvimento de software e de infraestrutura/operações de TI, que tradicionalmente trabalhavam separadamente.

Ao adotar o DevOps, as organizações conseguem melhorar a comunicação entre equipes e acelerar o ciclo de desenvolvimento, possibilitando atualizações e melhorias contínuas nos produtos.

Diferente dos modelos tradicionais de desenvolvimento e gerenciamento de infraestrutura, o DevOps favorece um **fluxo de trabalho mais ágil e integrado**, o que contribui para:

* Entregas mais frequentes.
* Maior qualidade do software.
* Menor tempo de resposta às demandas do mercado.

---

# A. Objetivos do DevOps

O DevOps tem como principal objetivo **reduzir o tempo do ciclo de desenvolvimento de sistemas**, permitindo que softwares de alta qualidade sejam entregues com **maior velocidade, confiabilidade e frequência**.

Para isso, essa metodologia busca **eliminar as barreiras entre as equipes de desenvolvimento (Dev) e operações de TI (Ops)**, promovendo integração em todas as etapas do processo, desde a criação do software até sua implementação em produção.

## Principais Metas e Benefícios

* **Velocidade de entrega**: Possibilita a liberação mais rápida de novas funcionalidades, melhorias e correções.
* **Confiabilidade e qualidade**: Por meio de práticas como monitoramento constante e integração, contribui para aumentar a estabilidade dos sistemas.
* **Colaboração**: Promove a integração entre equipes que antes trabalhavam de forma separada, incentivando o respeito e a cooperação profissional.
* **Resposta rápida ao mercado**: Com ciclos de desenvolvimento mais curtos, as empresas conseguem adaptar seus produtos rapidamente.

---

# B. Por que o DevOps surgiu?

O DevOps surgiu porque o **modelo tradicional de desenvolvimento de software estava gerando muitos problemas dentro das empresas de tecnologia**. Profissionais das áreas de desenvolvimento e operações perceberam que o isolamento das equipes causava atrasos, erros frequentes e dificuldades na entrega de software.

No modelo antigo:
* Os desenvolvedores eram responsáveis apenas por criar o código.
* Outra equipe cuidava de implantar, manter e operar o sistema.

Como essas equipes tinham objetivos diferentes, a comunicação limitada gerava falhas nas versões lançadas e insatisfação dos usuários. O movimento DevOps surgiu para aproximar essas áreas, incentivando a colaboração e o uso de ferramentas digitais para documentar e compartilhar o trabalho.

---

## 2. Características e Princípios do DevOps

O **DevOps** não é apenas uma ferramenta, mas uma mudança cultural que une o Desenvolvimento (Dev) e as Operações (Ops). Sua essência está em entregar valor ao cliente de forma rápida, segura e com alta qualidade.

---

### A. Princípios Fundamentais

Para realizar todo o potencial do DevOps, as equipes seguem estes pilares essenciais:

* **Colaboração (Culture):** Quebra os "silos" organizacionais. Desenvolvedores e Operações trabalham como uma única equipe funcional, compartilhando responsabilidades do início ao fim do produto.
* **Automação:** É o coração do ciclo. Automatizar o ciclo de vida do software reduz erros humanos, aumenta a produtividade e permite respostas rápidas ao feedback.
* **Melhoria Contínua:** Focada na experimentação e otimização constante de velocidade e custo, garantindo que o software evolua sempre.
* **Foco no Cliente:** Utiliza ciclos curtos de feedback para criar produtos que resolvam problemas reais, baseando-se em dados de uso real e não apenas suposições.
* **Criar com o Final em Mente:** As equipes têm uma compreensão holística do produto, da ideia inicial até a sustentação em produção.

---

### B. O Ciclo de Vida DevOps (DevOps Lifecycle)

Conforme visualizado na imagem do infinito ($\infty$), o ciclo divide-se entre as fases de construção e as fases de operação:

<p align="center">
  <img src="./Imagens/Ciclo%20Lifecycle%20.png" alt="Ciclo de Vida DevOps" width="500">
</p>

#### Lado DEV (Development)
1.  **Plan (Planejar):** Definição de requisitos, metas e alinhamento com as necessidades do usuário.
2.  **Create (Criar):** Fase de desenvolvimento, onde o código é escrito e as novas funções ganham forma.
3.  **Verify (Verificar):** Execução de testes automáticos para garantir a qualidade e segurança do código.
4.  **Package (Empacotar):** Transformação do código aprovado em um "pacote" pronto para ser implantado (artefato).

#### Lado OPS (Operations)
5.  **Release (Liberar):** Gerenciamento da entrega da nova versão para o ambiente de destino.
6.  **Configure (Configurar):** Preparação da infraestrutura, servidores e parâmetros para que o software rode perfeitamente.
7.  **Monitor (Monitorar):** Acompanhamento em tempo real da performance e da experiência do usuário.

---

> **IMPORTANTE:**
> <br>
> **Por que o Ciclo representa o Infinito?**
><br>
> O objetivo desta estrutura é criar um fluxo onde o **Monitoramento** (etapa 7) gera dados que retroalimentam o novo **Planejamento** (etapa 1). Isso garante um software sempre disponível, estável e em constante evolução.
---

3. Tipos de projetos mais adequados

Aqui você precisa descobrir onde DevOps é mais usado.

Exemplos de projetos que usam DevOps

Aplicações web

Sistemas em nuvem

Aplicativos mobile

Plataformas de streaming

Sistemas que recebem atualizações frequentes

## Exemplos de empresas que usam DevOps

Netflix

Amazon

Google

Facebook


4. Ferramentas associadas ao DevOps

Esse é um dos pontos mais importantes do trabalho.

Controle de versão

Git

GitHub

Integração contínua

Jenkins

GitLab

Containers

Docker

Orquestração

Kubernetes

Monitoramento

Prometheus

Grafana


5. Vantagens e desvantagens
Vantagens

Entrega de software mais rápida

Menos erros

Melhor colaboração entre equipes

Automação de processos

Atualizações constantes

Desvantagens

Implementação pode ser difícil

Exige mudança cultural na empresa

Necessita conhecimento técnico elevado

Pode exigir novas ferramentas


6. Exemplos reais de aplicação


A Netflix usa DevOps para:

lançar atualizações rapidamente

testar novas funcionalidades

manter alta disponibilidade

Outro exemplo:

A Amazon usa DevOps para implantar código milhares de vezes por dia.


7. Comparação com outras metodologias

Compare DevOps com:

Agile

Scrum

Waterfall

Exemplo de comparação
Metodologia	Foco
Waterfall	processo linear
Scrum	desenvolvimento ágil
DevOps	integração entre desenvolvimento e operações


8. Casos reais.

6️ Vantagens e desvantagens
7️ Comparação com outras metodologias
9.Conclusão

Importância do DevOps atualmente.
