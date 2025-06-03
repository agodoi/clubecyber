# 📖 Storytelling: Missão SafeNet

Hoje vocês fazem parte de uma equipe de segurança real: a SafeNet é uma empresa fictícia que atua com redes corporativas e está preocupada com vulnerabilidades na **camada física**. Cada dupla/trio recebeu um roteador/repetidor de marca genérica — um equipamento barato, popular, mas que esconde potenciais riscos físicos.

O objetivo da missão é auditar a segurança física **não pelo software ou configuração**, mas **pelo que se pode ver, tocar e interferir fisicamente**: cabos, conectores, portas, sinais e energia.

Lembrem-se: não adianta ter firewalls ou criptografia se alguém pode simplesmente puxar um cabo, desconectar a energia, induzir ruído ou acessar fisicamente a rede sem barreiras.

Vocês terão 60 minutos para explorar, anotar, testar e entregar este relatório. O time que apresentar as respostas mais criativas, detalhadas e conectadas à realidade ganhará destaque como “Top Agents”.


# 📝 Relatório para Preenchimento – Auditoria Física

## 1️⃣ Identificação

* Nome da dupla: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_
* Número do roteador/repetidor (marcação de bancada): \_\_\_\_\_\_\_\_\_\_\_\_\_
* Data: \_\_\_/\_\_\_/\_\_\_\_\_\_


## 2️⃣ Inspeção Física Inicial

* Quais elementos físicos do equipamento chamaram a atenção? (ex.: material da carcaça, proteção das portas, tipo de fonte de energia, etc.)

---

---

* Algum componente parece fácil de ser violado fisicamente (porta sem trava, botão de reset acessível, tampa solta, etc.)?

---

---

---

* O equipamento é homologado pela Agência Nacional de Telecomunicações - ANATEL. Siga esses passos para investigar:


  Entre site  [ANATEL](https://www.gov.br/anatel/pt-br). Precisa ter uma conta GOV.BR
      
            ↳   clique nos 3 tracinhos ≡ do canto esquerdo superior do site
            
               ↳   Vá em REGULADO
            
                  ↳ Vá em CERTIFICAÇÃO DE PRODUTOS
                  
                     ↳ Vá em CONSULTAR PRODUTOS HOMOLOGADOS

                        ↳ Digite o número que consta no corpo do equipamento XXXX - XX - XXXXX

                            ↳ Clique em FILTRAR ao invés de dar ENTER e aguarde o resultado

                                ↳ Clique na lupa para baixar a documentação do equipamento

                                    ↳ Clique no link Nº de Homologação


---

---
                   

## 3️⃣ Testes Físicos Realizados

✅ Teste 1: O que acontece ao desconectar fisicamente o cabo de rede enquanto o roteador está ativo?

---

✅ Teste 2: O que acontece ao gerar interferência física (ex.: enrolar um cabo elétrico próximo ao cabo de rede)? Alguma mudança no comportamento ou sinal?

---

✅ Teste 3: É possível desligar ou resetar o equipamento fisicamente sem ferramentas? Como?

---

---

## 4️⃣ Identificação de Vulnerabilidades Físicas

* Descreva **duas vulnerabilidades físicas reais** que encontraram e expliquem por que elas representam um risco à segurança cibernética:

1. ---

   Impacto esperado: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

2. ---

   Impacto esperado: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

---

## 5️⃣ Recomendações de Mitigação

* Quais soluções simples poderiam ser implementadas para mitigar os riscos físicos identificados?

---

---

* Como medidas físicas (como organização do cabeamento, uso de racks trancados, identificação de portas) ajudam a proteger contra ataques físicos?

---

---

---

## 6️⃣ Conclusão da Missão

* Em poucas palavras, descreva o maior aprendizado do grupo nesta tarefa:

---

---

---

## 7️⃣ Boas Práticas de Cabeamento Estruturado - Crimpagem do cabo UTP e Teste

Crimpar um cabo UTP (Unshielded Twisted Pair) Cat 5 exige atenção a alguns detalhes para garantir uma conexão eficiente e estável, livre de problemas, engenharia social e consequentemente, ataques. Sua missão é crimpar um cabo UTP CAT 5 com um conector RJ45 em cada ponta e passar no teste de condutividade. Usar o padrão 568A nas duas pontas. Você também pode optar pelo 568B nas duas pontas. Aqui estão as boas práticas para esse processo:

7️⃣.1️⃣ Escolha do Cabo e Conectores Corretos
   - Verifique se o cabo é compatível com o padrão Cat 5.
   - Utilize conectores RJ-45 adequados para cabos Cat 5 (ou Cat 5e).
   
7️⃣.2️⃣ Corte Limpo do Cabo
   - Utilize uma ferramenta de corte para garantir que o cabo seja cortado de forma reta e precisa, evitando fios desalinhados que podem dificultar a conexão.

7️⃣.3️⃣ Desencape o Cabo Com Cuidado
   - Ao remover a capa externa do cabo, deixe expostos cerca de 2,5 cm (1 polegada) dos pares trançados internos.
   - Não desencape, ou corte ou danifique os fios internos no momento de desencapar a capa externa.

7️⃣.4️⃣ Desenrolar e Organizar os Fios
   - Separe os pares de fios e os alinhe de acordo com o padrão escolhido (T568A ou T568B).
   - Certifique-se de que os fios estão alinhados e retos antes de inserir no conector.
   - Não desenrole demais os fios; mantenha a torção o mais próximo possível do conector, pois isso ajuda a minimizar interferências.

7️⃣.5️⃣ Escolha do Padrão Correto
   - Decida entre o padrão **T568A** ou **T568B** e certifique-se de seguir o mesmo padrão em ambas as extremidades do cabo, especialmente se estiver fazendo um cabo patch.
   - As combinações de cores para o padrão T568A são:
     - pino (1) Verde/Branco
     - pino (2) Verde
     - pino (3) Laranja/Branco
     - pino (4) Azul
     - pino (5) Azul/Branco
     - pino (6) Laranja
     - pino (7) Marrom/Branco
     - pino (8) Marrom
   - Para o padrão T568B (mais usado em redes residenciais):
     - pino (1) Laranja/Branco
     - pino (2) Laranja
     - pino (3) Verde/Branco
     - pino (4) Azul
     - pino (5) Azul/Branco
     - pino (6) Verde
     - pino (7) Marrom/Branco
     - pino (8) Marrom

#### Atenção: 

* Cabo Direto: sempre use cabo direto (568A - 568A ou 568B - 568B) quando estiver conectando dispositivos diferentes entre si.

* Cabo Cruzado: sempre use cabo cruzado (568A - 568B) quando estive conentando o mesmo tipo de equipamento.

* Sempre usamos as portas **Fast Ethernet** para conexão do RJ45 + cabo UTP de PC e **Giga Ethernet** para Switches e Roteadores.


7️⃣.6️⃣ Inserção Correta dos Fios no Conector
   - Certifique-se de que os fios estão perfeitamente alinhados e nivelados antes de inserir no conector RJ-45.
   - Pressione firmemente os fios dentro do conector até que cada um toque seu respectivo pino de metal.
   - O cabo externo (capa) deve estar preso dentro do conector para maior resistência e durabilidade.

7️⃣.7️⃣ Uso da Ferramenta de Crimpagem
   - Posicione o conector no alicate de crimpagem e aperte firmemente para fixar os contatos metálicos nos fios.
   - Certifique-se de que o conector está totalmente inserido no alicate antes de crimpar para evitar crimpar mal e danificar o conector.

7️⃣.8️⃣ Teste o Cabo
   - Após crimpar, utilize um **testador de cabos** para garantir que todos os fios estão corretamente conectados e o cabo está funcionando corretamente.
   - Verifique se todos os pares estão funcionando e se não há fios cruzados ou mal conectados.
