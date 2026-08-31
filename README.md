
# 📊 Sismógrafo IoT: Monitoramento de Vibrações e Extração de Dados com micro:bit

Um produto IoT desenvolvido para detectar, monitorar e registrar oscilações e impactos estruturais, transformando vibrações físicas em dados tabulados em tempo real.

## 🎯 Visão de Produto: O Problema e a Solução

**O Problema:** 
A detecção de vibrações anômalas, impactos em equipamentos ou movimentações estruturais indesejadas costuma depender de observação humana falha ou de equipamentos industriais de altíssimo custo. 

**A Solução (O Produto):** 
Desenvolvi um sismógrafo inteligente e acessível utilizando o acelerômetro embarcado no hardware micro:bit, programado em TypeScript. O sistema atua em duas frentes de resposta:
1. **Feedback Imediato (Front-end físico):** Emissão de um alerta sonoro (bip) instantâneo assim que a placa detecta uma oscilação que ultrapassa o limite de tolerância configurado.
2. **Inteligência de Dados (Back-end/Analytics):** O sistema exporta os dados de vibração (eixos X, Y e Z) via porta serial diretamente para o **Microsoft Excel**, criando um log contínuo de eventos.

## 👥 Usuários e Impacto
* **Público-alvo:** Profissionais de infraestrutura, técnicos de laboratório e educadores.
* **Impacto:** Permite o monitoramento contínuo de superfícies sensíveis. Os dados gerados ajudam a identificar padrões de trepidação em horários específicos, falhas em maquinários próximos ou comprovar a necessidade de isolamento acústico/físico no ambiente.

## 📈 Análise de Dados e Métricas
O valor deste produto está na transformação de movimento em inteligência de negócios.
* **Coleta Contínua:** Leitura constante da aceleração gravitacional nos três eixos tridimensionais.
* **Data Logging:** Envio serial contínuo para estruturação de tabelas no Excel.
* **Ações de Negócio:** Com os dados no Excel, é possível plotar gráficos de linha do tempo, identificar os horários exatos dos maiores picos de impacto e gerar relatórios de estabilidade do ambiente.

## 🛠️ Stack Tecnológico e Ferramentas
* **Hardware:** Placa micro:bit (acelerômetro e buzzer/piezo embarcados).
* **Linguagem:** TypeScript / Ecossistema MakeCode.
* **Análise de Dados:** Microsoft Excel (integração via porta serial com Data Streamer).

## 🚀 Como reproduzir este projeto

Para editar ou rodar este repositório diretamente no MakeCode:
1. Abra o ambiente [Microsoft MakeCode para micro:bit](https://makecode.microbit.org/).
2. Clique em **Importar** e depois em **Importar URL**.
3. Cole o link deste repositório (`https://github.com/Sandro-Clara/Sismografo-c-som`) e clique em importar.
4. Faça o flash do código para a sua placa micro:bit.
5. Com a placa conectada via USB, abra o Microsoft Excel e ative o suplemento **Data Streamer** para iniciar a captura de dados em tempo real.

---
*Desenvolvido por [Sandro Clara](https://github.com/Sandro-Clara) | Focado na interseção entre Hardware, Software e Análise de Produto.*

#### Metadados (usados para pesquisa, renderização)

* for PXT/microbit
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
