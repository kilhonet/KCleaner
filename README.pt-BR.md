# KCleaner

**Limpador de PC gratuito para Windows: com um clique, fecha todos os programas desnecessários e deixa só o que o Windows realmente precisa, e ainda organiza no mesmo lugar os itens de inicialização automática, os arquivos que sobraram e os programas de segurança instalados à força.**

[English](README.md) · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md) · Português (Brasil) · [Français](README.fr.md)

> Este documento é uma tradução. Em caso de divergência, a [versão em coreano](README.ko.md) prevalece.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011%20(64--bit)-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
![Version](https://img.shields.io/badge/version-4.0.0-blue)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/kcleaner?lang=pt)

![Tela do KCleaner](images/kcleaner-en.webp)

> A interface do programa não tem tradução para português; ela é exibida em inglês. Os nomes de botões e opções abaixo aparecem como na tela.

## Visão geral

Deixe o PC ligado por um tempo e uma porção de programas acaba rodando em segundo plano: mensageiros, assistentes de atualização, programas que você usou e não fechou, e até programas de segurança que sites de bancos fizeram você instalar. Encontrar e fechar um por um dá trabalho.

Com um único clique em **Clean** na guia **Home**, o KCleaner fecha tudo, menos os programas de que o Windows precisa para funcionar, e depois libera a memória restante. Drivers essenciais, como os de vídeo e som, e antivírus confiáveis não são fechados; programas disfarçados com o mesmo nome de programas do sistema do Windows são fechados. Os programas são apenas fechados, nunca desinstalados.

Além disso, ele traz três ferramentas de limpeza em guias:

- **Startup** — desativa, sem apagar, programas, tarefas agendadas e serviços que iniciam com o Windows.
- **Cleanup** — escolhe e apaga restos, como caches e arquivos temporários, deixados pelos aplicativos instalados.
- **Bundle** — encontra e remove programas de segurança que sites de bancos e órgãos públicos pediram para você instalar.

## Principais recursos

- **Fechar tudo de uma vez** — Um botão fecha todos os programas, menos os essenciais.
- **Critérios seguros** — Programas essenciais do Windows, drivers de vídeo e som e antivírus confiáveis são mantidos. Programas de sistema falsos, que só imitam nomes do Windows, são fechados.
- **Limpeza de memória** — Depois de fechar os programas, a memória restante é liberada.
- **Lista de exceções** — Você mesmo pode indicar programas que precisam continuar abertos para que não sejam fechados.
- **Resultados** — Ao terminar a limpeza, abre-se uma página de resultados com os programas fechados e a mudança na memória.
- **Gerenciamento da inicialização** — Ative e desative, em uma única lista, os itens de inicialização automática espalhados por pastas de inicialização, registro, Agendador de Tarefas e serviços.
- **Limpeza de arquivos que sobraram** — Analisa e apaga caches, arquivos temporários e logs apenas dos aplicativos instalados neste PC. Registros pessoais, como favoritos, senhas e histórico de navegação, vêm desmarcados por padrão.
- **Remover programas instalados à força** — Lista os programas de segurança de bancos e órgãos públicos e executa o desinstalador deles com um botão.
- **Ícone na bandeja** — A versão instalada fica esperando na área de notificação depois que você entra no Windows e abre com um clique.
- **Modo escuro** — As cores seguem o modo de aplicativo do Windows (claro · escuro).
- **9 idiomas** — Coreano · inglês · japonês · chinês · russo · italiano · francês · espanhol · árabe.

## Download / Instalação

| Tipo | Link |
|---|---|
| Instalador | [Download](https://down.kilho.net/kcleaner?lang=pt) |
| Portátil (ZIP) | [Download](https://down.kilho.net/kcleaner?lang=pt&nosetup) |

O instalador abre o KCleaner assim que a instalação termina e coloca um ícone na área de notificação. Na versão portátil, descompacte o ZIP e execute `KCleaner.exe`. As duas versões limpam do mesmo jeito; só a versão instalada tem o ícone na bandeja.

Fechar programas e alterar itens de inicialização automática exige permissões de administrador, por isso o Windows mostra uma janela de confirmação de administrador ao executá-lo. Clique em **Sim**.

## Como usar

### Primeiros passos

1. Se houver documentos abertos ou trabalho em andamento, salve primeiro. Todos os programas não essenciais, inclusive navegadores e mensageiros, serão fechados.
2. Execute o KCleaner e clique em **Sim** na janela de confirmação de administrador.
3. Na guia **Home**, clique em **Clean**.
4. Um indicador de progresso gira no lugar do botão enquanto os programas desnecessários são fechados e a memória é limpa.
5. Ao terminar, a página de resultados abre no navegador e a janela do KCleaner se fecha sozinha.

### Organização da tela

| Elemento | Função |
|---|---|
| **Home** | A primeira tela, com o botão **Clean** |
| **Startup** | Ativar e desativar itens que iniciam com o Windows |
| **Cleanup** | Analisar e apagar arquivos que sobraram dos aplicativos instalados |
| **Bundle** | Remover programas de segurança de bancos e órgãos públicos |
| Logotipo KILHO.net | Abre a página do KCleaner |

Cada guia carrega sua lista na primeira vez que você a abre. Se você só usa **Clean** na guia **Home**, não precisa abrir as outras guias.

**Startup**

| Elemento | Função |
|---|---|
| Coluna **Program** | Ícone e nome do programa (o nome do produto, quando houver) |
| Coluna **Source** | Onde o item está registrado — **Startup** (pasta de inicialização) · **Registry** · **Task** · **Service** |
| Linha cinza | Um item desativado |
| **All Programs** | Quando marcada, mostra tudo, inclusive os itens desativados |
| **Disable** / **Enable** | Desliga ou liga o item selecionado |
| Menu do botão direito | **Delete** (somente itens desativados) · **Save List** |

**Cleanup**

| Elemento | Função |
|---|---|
| Linha de categoria | **Windows** · nomes de navegadores · **Internet** · **Multimedia** · **Utilities** · **Applications** · **Games** · **Other**. Clique para expandir ou recolher |
| Linha de item | Um tipo de resto que pode ser apagado. Só os itens marcados são analisados e limpos |
| Ponto de exclamação | Um item que exige cuidado antes de apagar. Passe o mouse para ver uma observação (em inglês) |
| Coluna **Size** | Quanto pode ser apagado, depois de **Analyze** |
| Texto embaixo | Número de aplicativos instalados, andamento e resultados da análise ou da limpeza |
| **Analyze** / **Clean** | Encontra o que pode ser apagado e mostra o tamanho / apaga o que foi analisado |
| Menu do botão direito | **Select all** · **Select none** · **Restore defaults** |

**Bundle**

| Elemento | Função |
|---|---|
| Coluna **Program** | Programas de segurança de bancos e órgãos públicos instalados neste PC |
| Coluna **Source** | O fabricante (**Unknown** se não houver informação) |
| **Uninstall** | Executa o desinstalador do programa selecionado |

### O que fazer quando…

**O PC ficou lento e você quer limpar tudo de uma vez**
Basta clicar em **Clean** na guia **Home**. Os programas que rodavam em segundo plano são fechados juntos e a memória é liberada. Os programas são apenas fechados, não apagados; abra de novo os que precisar e use normalmente.

**Antes de clicar em Clean**
Programas não essenciais — navegadores, mensageiros, editores de documentos etc. — são fechados mesmo abertos. Se houver trabalho não salvo, salve primeiro. O Explorador do Windows e a área de trabalho, os drivers de vídeo e som e os antivírus confiáveis continuam rodando.

**Alguns programas precisam continuar abertos (lista de exceções)**
Na versão instalada, clique com o botão direito no ícone do KCleaner na área de notificação → **WhiteList**. O Bloco de Notas abre; escreva os programas que não devem ser fechados, um por linha, e salve.

- `programa.exe*` — o programa cujo nome de arquivo executável é exatamente igual (ex.: `editplus.exe*`)
- Sem `*` — todos os programas cujo caminho contém esse texto (ex.: `\EditPlus\` abrange todos os programas daquela pasta)

A partir do próximo clique em **Clean**, os programas da lista não são fechados. Na versão portátil, crie `NoClean.txt` ao lado de `KCleaner.exe` e preencha do mesmo jeito.

**Ver os resultados**
Ao terminar a limpeza, uma página de resultados abre no navegador com os programas fechados e a memória antes e depois. A janela do KCleaner se fecha sozinha quando o trabalho termina.

**Abrir direto pelo ícone da bandeja**
Na versão instalada, o ícone do KCleaner aparece na área de notificação pouco depois de você entrar no Windows. Um clique com o botão esquerdo abre o KCleaner; se ele já estiver aberto, a janela vem para a frente. O menu do botão direito tem **KCleaner** · **WhiteList** · **About** · **Quit**. **Quit** tira o ícone até a próxima vez que você entrar no Windows.

**Desligar programas que iniciam com o Windows**
Na guia **Startup**, clique no programa e em **Disable**. O item não é apagado, apenas desligado: deixa de iniciar a partir da próxima inicialização, e o programa continua funcionando como antes. A linha fica no lugar, em cinza, para você poder religá-la na hora com **Enable**.

**Ligar de novo um item desativado**
Na guia **Startup**, marque **All Programs** e os itens desativados antes aparecem como linhas cinza. Clique na linha e em **Enable**: ele volta a ser executado a partir da próxima inicialização.

**Desligar tarefas de atualização e serviços**
Linhas cuja **Source** é **Task** rodam sozinhas em horários definidos; linhas **Service** são serviços em segundo plano que iniciam com o Windows. **Disable** impede que uma tarefa rode mesmo quando chega o horário, e que um serviço inicie com o Windows ou quando outro programa o chama. É melhor verificar a qual programa um serviço pertence antes de desligá-lo.

**Você não sabe o que é um item de Startup**
Dê um clique duplo na linha e o navegador abre com informações sobre esse item.

**Sobraram entradas de inicialização de um programa desinstalado**
Primeiro mude a linha para **Disable**, depois clique com o botão direito → **Delete** e clique em **Sim** para confirmar. Itens excluídos não podem ser recuperados, então exclua apenas o que você tem certeza de que não precisa. Excluir um serviço mostra o aviso "A service that was running is fully removed after a restart" — reinicie o PC uma vez e ele some de vez.

**Guardar uma cópia da lista de inicialização**
Na guia **Startup**, clique com o botão direito → **Save List** para salvar em um arquivo de texto todos os itens de inicialização automática, inclusive os itens essenciais do Windows ocultos na lista. Serviços e tarefas de que o Windows precisa ficam ocultos desde o início para você não desativá-los por engano, e continuam ocultos mesmo com **All Programs** marcada.

**Recuperar espaço em disco apagando arquivos que sobraram**
Na primeira vez que você abre a guia **Cleanup**, o KCleaner procura os aplicativos instalados neste PC, informa como **N installed apps** e mostra, por categoria, só os itens de limpeza desses aplicativos. Mantenha as marcações padrão e clique em **Analyze** para ver quais arquivos seriam apagados e quanto espaço ocupam; clique em **Clean** para apagar o que foi analisado. **Analyze** não apaga nada, então você pode usá-lo só para ver quanto espaço conseguiria liberar.

**Escolher você mesmo o que apagar**
Clique em uma linha de categoria para expandi-la e ver os itens; clique em uma linha de item para trocar a marcação. A caixa da linha de categoria marca ou desmarca a categoria inteira de uma vez e fica cinza quando só alguns itens estão marcados. Suas mudanças são lembradas e usadas na próxima vez que você abrir a guia. Para voltar ao estado original, clique com o botão direito na lista → **Restore defaults**.

**Você também quer apagar o histórico de navegação ou as listas de arquivos recentes**
Registros criados por você — favoritos, senhas, histórico de navegação, histórico de conversas — vêm desmarcados por padrão para não serem apagados por engano. Para aplicativos que misturam caches com listas de arquivos recentes, existe um item separado chamado **… · Usage history**. Se quiser apagar esses registros também, marque esse item você mesmo.

**Não dá para clicar em Clean**
**Clean** só fica ativo depois que todos os itens marcados passaram por **Analyze** e há algo para apagar. Se você marcou itens novos depois da análise, ou acabou de terminar uma limpeza, clique em **Analyze** mais uma vez.

**Itens com ponto de exclamação**
São itens com algo a saber antes de apagar. Passe o mouse sobre o sinal para ler a observação (em inglês); se algum deles estiver marcado, você terá de confirmar mais uma vez ao clicar em **Clean**.

**O navegador está aberto**
Arquivos em uso não são tocados e ficam de fora. Para limpar mais o cache do navegador, feche-o antes de limpar, ou clique primeiro em **Clean** na guia **Home** e depois faça a limpeza.

**Meus arquivos estão seguros?**
As pastas Documentos, Área de Trabalho, Imagens, Vídeos, Músicas e Downloads, além dos arquivos ocultos e de sistema, nunca são analisadas nem limpas. Com conexão à internet, a lista de limpeza é trocada automaticamente pela versão revisada mais recente.

**Remover programas de segurança que um site de banco instalou**
Abra a guia **Bundle** para ver só os programas de segurança de bancos e órgãos públicos instalados neste PC — segurança de teclado, certificados digitais, firewalls e similares. Selecione um e clique em **Uninstall**, ou dê um clique duplo na linha, e o desinstalador do próprio programa abre, igual a "Desinstalar um programa" no Painel de Controle. Quando a remoção termina, ele sai da lista sozinho. Se não houver nada a remover, a guia mostra **Nothing to uninstall**. Você sempre pode reinstalar pelo site quando precisar.

**Navegar pelas listas com o teclado**
Nas guias **Startup** e **Bundle**, use **↑** · **↓** para passar de uma linha a outra; **F5** recarrega a lista. Se os nomes aparecerem cortados, arraste a divisa entre os cabeçalhos das colunas para ajustar a largura.

**Executar de novo quando já está aberto**
Só um KCleaner roda por vez. Executá-lo de novo com a janela aberta não abre uma nova cópia; a janela que já está aberta vem para a frente.

## Configuração

Não há nada a configurar. Os programas que devem continuar abertos vão na lista de exceções acima, e as marcações da guia Cleanup são lembradas conforme você as muda na tela. O KCleaner segue sozinho o seguinte:

| Item | Segue |
|---|---|
| Idioma | A configuração regional do Windows (inglês se o idioma não for suportado — é o caso do português) |
| Cores | O modo de aplicativo do Windows (claro · escuro) — mudanças são aplicadas na hora, mesmo com o KCleaner aberto |

## Requisitos

- Windows 10 · Windows 11 (64 bits)
- Permissões de administrador — necessárias para fechar programas e alterar itens de inicialização automática. Uma janela de confirmação aparece ao executá-lo.
- Nenhum outro componente precisa ser instalado.
- A conexão à internet é usada para avisos de novas versões, atualização das listas e a página de resultados. Sem conexão, a limpeza funciona normalmente com as listas embutidas.

## Atualizações

O KCleaner **não** se atualiza sozinho. Ao iniciar, ele verifica se há uma nova versão e mostra um aviso; clicar em **[Sim]** abre a página de download e fecha o programa. Novas versões são lançadas manualmente após verificação interna e anunciadas na [página do KCleaner](https://kilho.net/kcleaner). Consulte o [aviso sobre a política de atualizações](https://en.kilho.net/archives/notice/2940).

**Histórico de versões**

| Versão | Data | Alterações |
|---|---|---|
| 4.0.0 | 2026-10-01 | Refeito em Rust para mais estabilidade, novo recurso de limpeza de arquivos (escolha o que remover), listas de programas de inicialização e serviços mais fáceis de gerenciar |
| 3.8.8 | 2026-07-15 | Otimização de memória mais rápida e confiável, exibição da área de trabalho mais estável em diferentes PCs, execução mais rápida com uma limpeza simplificada, gerenciamento de memória eficiente focado no navegador, espanhol adicionado |
| 3.8.7 | 2026-04-15 | Clean funciona de forma estável mesmo com interferência de software de segurança, certificado de assinatura de código aplicado e assinatura aprimorada |
| 3.8.6 | 2026-03-19 | Gerenciamento de memória mais eficiente, processamento interno otimizado para uma resposta mais rápida do sistema, menos uso desnecessário de memória para uma experiência mais fluida, melhorias gerais de desempenho |

## Licença

O KCleaner é **freeware**. Use-o de graça e sem restrições em qualquer lugar — no trabalho, em casa, em órgãos públicos ou na escola — e redistribua-o livremente.

A lista do Cleanup é baseada no [Winapp2](https://github.com/MoscaDotTo/Winapp2) (CC BY-SA 4.0). As licenças dos componentes usados estão em `THIRD-PARTY-NOTICES.txt`, na pasta de instalação.

## Links

- Site: <https://kilho.net/kcleaner>
- Fórum: <https://kilho.top/forum/qna>
- X (Twitter): <https://www.twitter.com/kilhonet>

© KILHO.NET
