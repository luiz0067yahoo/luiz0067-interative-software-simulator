=== Simulador de Software Interativo ===
Contributors: luiz0067
Donate link: https://profiles.wordpress.org/luiz0067/
Tags: simulator, tutorial, gutenberg, interactive, software
Requires at least: 6.0
Tested up to: 6.7
Requires PHP: 7.4
Stable tag: 1.0.0
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Bloco Gutenberg nativo para criar tutoriais e simulações guiadas passo a passo de softwares reais com camadas interativas responsivas.

== Description ==

O **Simulador de Software Interativo** é um bloco Gutenberg nativo de alta performance para WordPress projetado para criar **tutoriais práticos guiados passo a passo simulando softwares reais** (como Windows 11, Microsoft Word, Excel, painéis SaaS, sistemas operacionais e ferramentas web).

O bloco permite enviar capturas de tela (prints) em alta resolução e desenhar camadas interativas responsivas (áreas de clique com pulso visual e caixas de digitação com validação instantânea).

= Principais Funcionalidades =

* **Coordenadas 100% Responsivas por Porcentagem (%)**: Todos os hotspots e campos de input utilizam `top`, `left`, `width` e `height` em `%`. A simulação funciona com precisão em celulares, tablets, notebooks e telas de alta resolução.
* **Frontend Ultraleve em Vanilla JavaScript**: Zero dependências pesadas no lado do cliente. Carregamento instantâneo, seguro e em conformidade com as diretrizes do WordPress Core.
* **Isolamento de Estado (Multi-Instance)**: Cada bloco inserido na página opera em seu próprio escopo, permitindo múltiplos simuladores na mesma postagem sem colisão de variáveis.
* **Validação Inteligente de Digitação**: Compara o texto inserido com o valor esperado (case-insensitive, tolerante a formatações como "3" ou "3 cm").
* **Feedback Tátil & Visual**: Pulso suave de destaque nas áreas clicáveis, animação de vibração (shake) e aviso flutuante (toast) ao errar ou clicar fora da área indicada.
* **Suporte Multi-Input com Botão de Confirmação**: Suporta etapas com múltiplos campos preenchíveis simultaneamente (como janelas modais com vários campos de formulário).
* **Modo Tela Cheia**: Suporte nativo à Fullscreen API com adaptação automática de proporção.
* **Cenário de Exemplo Embutido**: Já vem pré-carregado com o fluxo completo de **Formatação de Margens ABNT no Windows 11** com ilustrações vetoriais SVG de altíssima fidelidade.

== Installation ==

1. Faça o upload do arquivo ZIP através do painel do WordPress em **Plugins > Adicionar Novo Plugin > Enviar Plugin**, ou descompacte a pasta dentro de `/wp-content/plugins/`.
2. Ative o plugin através do menu **Plugins** no WordPress.
3. Abra qualquer post ou página no editor de blocos Gutenberg.
4. Insira o bloco digitando `/simulador` ou selecionando **Simulador de Software Interativo** na categoria **Mídia**.

== Frequently Asked Questions ==

= O plugin precisa de alguma biblioteca externa no frontend? =
Não. O frontend player foi escrito inteiramente em Vanilla JavaScript puro, sem bibliotecas pesadas de terceiros.

= As simulações funcionam bem no celular? =
Sim. Como todas as posições dos botões e campos de entrada são calculadas proporcionalmente em porcentagem (%), o layout se ajusta perfeitamente a smartphones e tablets.

= Posso criar simulações de qualquer software? =
Sim! Basta adicionar as capturas de tela dos passos desejados pela Biblioteca de Mídia e posicionar as áreas interativas correspondentes pelo painel lateral do bloco.

== Screenshots ==

1. Painel lateral do editor Gutenberg com gerenciamento de passos e configuração de camadas interativas.
2. Passo 1 da simulação demonstrativa: Área de trabalho do Windows 11 com botão Iniciar destacado.
3. Passo 2: Menu Iniciar com pesquisa interativa.
4. Passo 3: Microsoft Word aberto com indicação para acessar a aba Layout.
5. Passo 4: Menu suspenso de Margens.
6. Passo 5: Janela modal de Configuração de Página com múltiplos inputs numéricos ABNT.
7. Tela final com mensagem de parabéns e botão de reiniciar.
8. Adaptação responsiva em telas móveis.

== Changelog ==

= 1.0.0 =
* Lançamento oficial do bloco Simulador de Software Interativo.
* Suporte a áreas clicáveis (hotspots) com animação pulsante.
* Suporte a campos de digitação com validação dinâmica.
* Suporte a múltiplos formulários/etapas simultâneas.
* Cenário demonstrativo completo de Formatação de Margens ABNT no Windows 11 pré-integrado.
