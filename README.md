# Manual do MacGyver

Nov 1, 2026 · @Marinaldo

## Visão geral

O MacGyver é um canivete suíço digital: 14 ferramentas de uso diário num único aplicativo que roda no navegador do celular e funciona sem internet.

Três princípios guiam o app. Ele é **offline**: depois da primeira abertura, todos os arquivos ficam guardados no aparelho. Ele é **local**: tudo o que você salva fica no seu navegador e nada é enviado a servidores. Ele é **simples**: sem cadastro, sem anúncios, sem rastreio e sem bibliotecas externas. Pode ser instalado na tela inicial como um aplicativo comum (PWA).

| # | Ferramenta | Para que serve | Guarda dados no aparelho |
| --- | --- | --- | --- |
| 1 | Calculadora | Contas com parênteses e porcentagem | Não |
| 2 | Notas | Anotações com lista, busca e edição | Sim |
| 3 | Senhas | Gerar senhas seguras e aleatórias | Não |
| 4 | Conversor | Medidas, peso, temperatura, dados e mais | Não |
| 5 | Cronômetro | Medir tempo com parciais | Não |
| 6 | Timer | Contagem regressiva com alarme | Último tempo usado |
| 7 | Contador | Vários contadores com vibração | Sim |
| 8 | Lanterna | Tela cheia colorida como fonte de luz | Cor escolhida |
| 9 | SOS | Sinal de socorro em código Morse | Não |
| 10 | Remédios | Horários e doses de medicamentos | Sim |
| 11 | Sorteio | Dados, moeda, lista e números | Não |
| 12 | Divisor | Dividir a conta com gorjeta | Não |
| 13 | Metrônomo | Ritmo de 30 a 240 BPM | Último BPM |
| 14 | Datas | Diferença, soma de dias e idade | Não |

## Instalação e primeiros passos

Abra o endereço do app uma vez com internet; depois disso ele funciona também em modo avião.

1. Abra o endereço do GitHub Pages, no formato `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`, no Chrome (Android) ou no Safari (iPhone).
2. **Android:** toque em "Instalar aplicativo" na tela inicial do MacGyver. Se o botão não aparecer, abra o menu do navegador e escolha "Instalar app" ou "Adicionar à tela inicial".
3. **iPhone:** toque em Compartilhar e depois em "Adicionar à Tela de Início".
4. Abra o ícone MacGyver na tela inicial do celular. O app abre em tela cheia, sem a barra do navegador.
5. Para conferir o modo offline, ative o modo avião e abra o app de novo.

A primeira abertura precisa de internet para baixar os arquivos. Se você abrir só pelo navegador, sem instalar, tudo funciona do mesmo jeito; a instalação apenas dá acesso mais rápido.

## Uso geral

Toda ferramenta abre com um toque no cartão da tela inicial, e a barra superior é igual em todas elas.

- **Tela inicial:** grade com os 14 cartões. Toque em um para abrir a ferramenta.
- **Seta de voltar:** leva de volta à tela inicial. O botão ou gesto de voltar do próprio aparelho faz o mesmo.
- **Botão de sol/lua:** alterna entre modo escuro e modo claro. Na primeira abertura o app segue o tema do aparelho; depois disso ele lembra a sua escolha.
- **Indicador online/offline:** aparece em verde quando há internet e em âmbar quando não há. Serve só de informação, pois o app funciona igual nos dois casos.
- **Som:** os bipes e alarmes dependem do volume do aparelho. No iPhone, o interruptor de silencioso pode calar os sons do app.
- **Vibração:** usada no contador, no sorteio e em alguns alertas. O Safari do iPhone não permite vibração por aplicativos web, então no iPhone ela não acontece.
- **Toque antes do som:** os navegadores só liberam áudio depois de um toque seu. Por isso o som começa sempre a partir de um botão que você aperta, como Iniciar ou Ativar.

## 1. Calculadora

A calculadora resolve contas completas, respeitando a ordem das operações e os parênteses, e mostra o resultado enquanto você digita.

| Tecla | Função |
| --- | --- |
| C | Limpa a conta inteira |
| ⌫ | Apaga o último caractere |
| ( ) | Abre e fecha parênteses |
| ÷ × − + | Dividir, multiplicar, subtrair e somar |
| % | Divide o número anterior por 100 |
| = | Calcula e mantém o resultado para continuar a conta |

Exemplos: `2+3×4` dá 14, e `(2+3)×4` dá 20. Para somar 10% a 200, digite `200+200×10%`, que dá 220, porque o botão % apenas divide por 100.

Digite os decimais com ponto. O resultado aparece no formato brasileiro, com vírgula decimal e ponto nos milhares. Depois do =, tocar num operador continua a conta com o resultado; tocar num número começa uma conta nova. Se a expressão estiver incompleta ou houver divisão por zero, o app mostra "Erro" ao tocar em =. Os cálculos têm precisão de 12 dígitos.

## 2. Notas

O bloco de notas tem uma única tela: o campo para escrever fica no topo e a lista de notas logo abaixo, sempre visível.

1. Escreva no campo "Nova nota".
2. Toque em **Salvar nota**. A nota aparece no topo da lista na mesma hora, com um destaque rápido e o aviso "Nota salva".
3. Para editar, toque na nota. O texto vai para o campo e o botão vira **Salvar alterações**. Toque em **Cancelar** para desistir.
4. Em cada nota há os botões **Copiar** (copia o texto) e **Excluir** (pede confirmação).
5. Use o campo de busca para filtrar a lista por qualquer trecho do texto.

O título da lista mostra o total de notas, como "Minhas notas (3)". As notas ficam ordenadas da alteração mais recente para a mais antiga. O que você digita e ainda não salvou fica guardado como rascunho e volta se você sair e reabrir o app.

As notas ficam somente no navegador deste aparelho. Se o navegador bloquear o armazenamento, o app avisa na hora que as notas não serão mantidas ao fechar. Veja a seção sobre privacidade e dados para saber como preservar notas importantes.

## 3. Senhas

O gerador cria senhas aleatórias com o gerador criptográfico do navegador, o mesmo tipo usado por gerenciadores de senha.

- **Tamanho:** de 8 a 64 caracteres (começa em 20), ajustado pelo controle deslizante.
- **Tipos de caractere:** maiúsculas, minúsculas, números e símbolos (`!@#$%^&*()-_=+[]{};:,.?/`). A senha sempre inclui pelo menos um caractere de cada tipo marcado.
- **Evitar caracteres ambíguos:** tira O, 0, I, l, 1 e | para facilitar a leitura e a digitação manual.
- **Gerar** cria uma nova senha, e **Copiar** manda a senha para a área de transferência.

A senha muda sozinha sempre que você mexe no tamanho ou nas opções. Abaixo dela o app estima a força em bits de entropia: menos de 50 bits é fraca, de 50 a 79 é boa, de 80 a 109 é forte e a partir de 110 é excelente.

O app não guarda as senhas geradas. Ao sair da ferramenta, elas se perdem; copie e salve a senha num gerenciador de senhas antes de usá-la.

## 4. Conversor

O conversor troca valores entre unidades de nove categorias, com fórmulas calculadas no próprio aparelho.

| Categoria | Unidades |
| --- | --- |
| Comprimento | mm, cm, m, km, polegada, pé, jarda, milha, milha náutica |
| Massa | mg, g, kg, tonelada, onça, libra, pedra |
| Volume | mL, L, m³, colher de chá, colher de sopa, xícara, fl oz (EUA), galão (EUA) |
| Área | cm², m², km², hectare, acre, pé² |
| Velocidade | m/s, km/h, mph, nó |
| Tempo | ms, s, min, h, dia, semana |
| Dados | bit, B, KB, MB, GB, TB (cada nível vale 1024 do anterior) |
| Pressão | Pa, kPa, bar, atm, psi, mmHg |
| Temperatura | °C, °F, K |

Escolha a categoria, depois as unidades **De** e **Para**, e digite o valor. O resultado aparece em destaque, e o botão ⇄ troca as duas unidades. O quadro "Todas as unidades" mostra o mesmo valor convertido para todas as outras unidades da categoria de uma só vez.

O campo de valor aceita vírgula ou ponto como separador decimal. Nas medidas de cozinha, a xícara vale 240 mL, a colher de sopa 15 mL e a colher de chá 5 mL.

## 5. Cronômetro

O cronômetro mede o tempo em centésimos de segundo e registra quantas parciais você quiser.

- **Iniciar** começa a contagem. Durante a contagem o mesmo botão vira **Pausar**, e depois da pausa vira **Continuar**.
- **Parcial** registra uma volta sem parar o relógio. Só funciona com o cronômetro rodando.
- **Zerar** para tudo e apaga as parciais.

O visor mostra minutos, segundos e centésimos, e passa a mostrar horas quando o tempo chega a 1 hora. Cada linha da lista traz o número da parcial, o tempo daquela volta e, em cinza, o total acumulado. A partir da terceira parcial, a volta mais rápida aparece em verde e a mais lenta em vermelho.

A contagem continua se você trocar de ferramenta dentro do app, mas se o app for fechado o tempo se perde. Em medições longas, mantenha a tela ligada.

## 6. Timer

O timer faz uma contagem regressiva e avisa o fim com tela piscando, som e vibração.

1. Digite as horas, os minutos e os segundos, até 99 horas. Ou toque num atalho: 1, 3, 5, 10, 15, 30 ou 60 minutos.
2. Toque em **Iniciar**. A tela passa a mostrar o tempo restante e uma barra de progresso.
3. Use **Pausar** e **Continuar** quando precisar, ou **Zerar** para cancelar.
4. Ao chegar a zero, a tela pisca em vermelho e branco, soa uma sequência de três bipes a cada pouco mais de um segundo e o aparelho vibra. Toque em **PARAR** para silenciar.

O app lembra o último tempo que você usou. A contagem se baseia no relógio do aparelho, então não atrasa se o navegador ficar lento.

O alarme só toca com o app aberto. Se você bloquear a tela ou trocar de aplicativo por muito tempo, o navegador pode suspender o MacGyver e o aviso não soará. Para tempos críticos, mantenha o app em primeiro plano ou use também o alarme do sistema.

## 7. Contador

O contador permite manter vários totais ao mesmo tempo, cada um com nome próprio, e vibra a cada toque.

- Toque em **+** para somar 1 e em **−** para subtrair 1. Cada toque dá uma vibração curta e o valor pode ficar negativo.
- Toque no nome do contador para renomeá-lo, por exemplo "Pessoas na fila" ou "Séries feitas".
- **Zerar** volta o contador a 0 e pede confirmação quando o valor não é zero.
- O **✕** exclui o contador, também com confirmação.
- **+ Novo contador** adiciona mais um cartão.

Os contadores são salvos automaticamente a cada toque e continuam como estavam quando você reabre o app.

## 8. Lanterna

A lanterna transforma a tela inteira numa fonte de luz de cor sólida, útil para iluminar um ambiente escuro.

1. Escolha a cor: **Branca** (luz mais forte), **Quente** (tom amarelado, mais confortável) ou **Vermelha** (preserva a visão noturna).
2. Toque em **Ligar lanterna**. A tela fica inteira na cor escolhida; o app tenta entrar em tela cheia e manter a tela acesa, quando o aparelho permite.
3. Toque em qualquer ponto da tela para desligar.

Esta ferramenta usa a tela, não o flash da câmera. A web não consegue controlar o brilho do aparelho, então suba o brilho ao máximo antes de ligar. O app lembra a última cor escolhida. A lanterna desliga sozinha se você voltar à tela inicial ou trocar de ferramenta.

## 9. SOS

O SOS pisca a tela e apita em código Morse, repetindo o sinal internacional de socorro até você parar.

O padrão é `··· −−− ···` (três pontos, três traços, três pontos). Cada ponto dura 0,22 segundo e cada traço 0,66 segundo. Entre as repetições há uma pausa de cerca de 1,5 segundo.

1. Marque ou desmarque **Bipe sonoro** e **Vibração**, conforme a situação.
2. Toque em **ATIVAR SOS**. A tela vai para preto e branco piscando, o bipe soa a 880 Hz e o aparelho vibra no mesmo ritmo.
3. Toque em **PARAR** para encerrar. Voltar à tela inicial também encerra o sinal.

O SOS é um sinal visual e sonoro de apoio e não envia mensagem nem chama ninguém. Numa emergência real, ligue primeiro para 190 (Polícia), 192 (SAMU) ou 193 (Bombeiros).

## 10. Remédios

O organizador de remédios guarda seus medicamentos e horários e mostra, a cada dia, o que já foi tomado e o que ainda falta.

**Cadastrar um medicamento**

1. Em "Novo medicamento", digite o **nome** e, se quiser, a **dose** (por exemplo, "50 mg" ou "1 comprimido").
2. Escolha um horário no campo de hora e toque em **Adicionar**. Repita para cada horário do dia; eles aparecem como botões que você pode tocar para remover.
3. Toque em **Salvar medicamento**.

**Acompanhar o dia**

- O quadro **Próxima dose** mostra o próximo horário ainda não tomado e avisa quantas doses de hoje estão atrasadas.
- A lista **Hoje** reúne todas as doses em ordem de horário. Toque em **Marcar** quando tomar; o botão vira "Tomado". Tocar de novo desfaz a marcação.
- Doses atrasadas ficam em vermelho. As marcações valem só para o dia: no dia seguinte tudo volta a ficar pendente, e os medicamentos cadastrados continuam.
- Em **Cadastrados** você vê todos os medicamentos e pode excluir qualquer um.

**Alertas**

No minuto exato de cada dose não marcada, o app mostra um aviso na tela, vibra e toca três bipes. Isso só acontece com o app aberto na tela; com o app fechado ou o celular bloqueado, nenhum alerta é emitido. Para medicamentos que não podem ser esquecidos, use também o alarme do sistema.

Este organizador é um lembrete pessoal e não substitui a orientação do seu médico ou farmacêutico.

## 11. Sorteio

O sorteio reúne quatro formas de decidir no acaso, todas com o gerador aleatório criptográfico do navegador, sem favorecer nenhum resultado.

- **Dados:** escolha o tipo (d4, d6, d8, d10, d12, d20 ou d100) e a quantidade de 1 a 10 dados, e toque em **Rolar**. O visor mostra a soma e, abaixo, o valor de cada dado.
- **Cara ou coroa:** toque em **Lançar moeda**.
- **Sortear da lista:** escreva um nome por linha e toque em **Sortear**. Linhas vazias são ignoradas, e um nome repetido tem mais chance de sair.
- **Número aleatório:** informe o mínimo e o máximo, que entram no sorteio, e toque em **Gerar**. Se você inverter os dois valores, o app corrige a ordem sozinho.

Os resultados não ficam guardados; cada novo sorteio substitui o anterior.

## 12. Divisor de conta

O divisor calcula a gorjeta, o total e quanto cada pessoa paga, em reais.

1. Digite o **valor da conta**.
2. Escolha a **gorjeta**: 0%, 5%, 10%, 12%, 15% ou 20%. O padrão é 10%.
3. Informe o número de **pessoas** com os botões − e +, ou digitando. O mínimo é 1.
4. Marque **Arredondar valor por pessoa para cima** se quiser que cada um pague um valor inteiro em reais.

O app mostra a gorjeta, o total e o valor por pessoa. Exemplo: numa conta de R$ 200,00 com gorjeta de 10% e 3 pessoas, a gorjeta é R$ 20,00, o total é R$ 220,00 e cada pessoa paga R$ 73,33, ou R$ 74,00 com o arredondamento. Com o arredondamento, a soma das partes fica um pouco acima do total, e a diferença funciona como gorjeta extra.

## 13. Metrônomo

O metrônomo marca o ritmo com batidas precisas entre 30 e 240 BPM (batidas por minuto).

- **Ajuste do andamento:** use o controle deslizante ou os botões −5, −1, +1 e +5. O valor inicial é 100 BPM.
- **Tempos por compasso:** escolha de 2 a 8. O primeiro tempo soa mais agudo e acende o ponto verde; os demais soam mais graves e acendem pontos âmbar.
- **Iniciar / Parar:** liga e desliga o ritmo. Ele também para sozinho se você sair da ferramenta.
- **Tap tempo:** toque no botão no ritmo desejado, no mínimo duas vezes, e o app calcula o BPM pela média dos últimos seis toques. Se você ficar mais de 2 segundos sem tocar, a contagem recomeça.

As batidas são agendadas pelo relógio de áudio do aparelho, o que mantém o ritmo estável mesmo quando a tela está ocupada. O último BPM usado fica salvo.

## 14. Datas

A ferramenta de datas faz três cálculos de calendário, todos prontos assim que você escolhe as datas.

**Diferença entre datas.** Escolha "De" e "Até" (a ordem não importa). O app mostra o intervalo em anos, meses e dias e, abaixo, o total de dias e de semanas. Exemplo: de 29/02/2024 a 01/11/2026 são 2 anos, 8 meses e 3 dias, ou 976 dias.

**Somar ou subtrair dias.** Informe a data inicial e o número de dias; use um número negativo, como −45, para voltar no tempo. O resultado vem com o dia da semana por extenso. Exemplo: 45 dias antes de 01/11/2026 é quinta-feira, 17 de setembro de 2026.

**Idade e aniversário.** Informe a data de nascimento. O app mostra a idade exata em anos, meses e dias, quantos dias faltam para o próximo aniversário e quantos dias você já viveu. No dia do aniversário aparece uma mensagem de parabéns. Quem nasceu em 29 de fevereiro tem o aniversário contado em 1º de março nos anos que não são bissextos.

Os campos começam preenchidos com a data de hoje. Os cálculos não são afetados por fuso horário nem por horário de verão.

## Privacidade, dados salvos e backup

Tudo o que o MacGyver guarda fica no armazenamento local do navegador, no seu aparelho; o app não tem conta, não envia dados e não usa anúncios nem estatísticas de uso.

| Fica salvo no aparelho | Não fica salvo |
| --- | --- |
| Notas e o rascunho em andamento | Contas da calculadora |
| Contadores e seus nomes | Senhas geradas |
| Medicamentos e horários cadastrados | Tempo do cronômetro e parciais |
| Marcações de dose do dia atual | Resultados de sorteios |
| Tema claro ou escuro | Valores do conversor, do divisor e das datas |
| Último tempo do timer, cor da lanterna e último BPM |  |

Os dados pertencem a um navegador e a um endereço. Abrir o app em outro navegador, em outro aparelho ou por outro endereço mostra tudo vazio. Limpar os dados do site nas configurações do navegador apaga tudo, e o modo anônimo pode não guardar nada. O app não sincroniza entre aparelhos nem exporta arquivos.

Para preservar uma nota importante, use o botão **Copiar** e cole o texto em outro lugar, como uma mensagem para você mesmo ou um e-mail.

## Limitações conhecidas e solução de problemas

O MacGyver é um aplicativo web, e a maior parte dos limites vem do que os navegadores permitem a um app web.

| Problema | Causa provável | O que fazer |
| --- | --- | --- |
| Timer ou lembrete de remédio não tocou | O app estava fechado ou o celular bloqueado e o navegador suspendeu o app | Mantenha o app aberto e a tela ligada; para itens críticos, use também o alarme do sistema |
| Sem som | Volume baixo, modo silencioso do iPhone ou nenhum toque antes do som | Aumente o volume, desative o silencioso e inicie o som por um botão do app |
| Sem vibração | O iPhone não permite vibração por apps web; alguns aparelhos têm a vibração desligada | Use o som e a tela como aviso |
| Lanterna fraca | O app não controla o brilho e não usa o flash da câmera | Suba o brilho da tela ao máximo e use a cor Branca |
| Tela cheia não ocorre | Alguns navegadores, principalmente no iPhone, limitam o modo de tela cheia | A tela colorida continua cobrindo o app e a ferramenta funciona normalmente |
| Botão "Instalar aplicativo" não aparece | O app já está instalado ou o navegador não oferece o botão | Use o menu do navegador: "Instalar app" ou "Adicionar à tela inicial" |
| App mostra versão antiga após uma atualização | O aparelho ainda usa a cópia guardada | Feche o app por completo e abra duas vezes; se persistir, limpe os dados do site (isso apaga as notas) |
| Notas ou medicamentos sumiram | Dados do site foram limpos, ou o app foi aberto em outro navegador, aparelho ou modo anônimo | Abra no mesmo navegador de antes; sem cópia, os dados não são recuperáveis |
| Calculadora mostra "Erro" | Expressão incompleta ou divisão por zero | Toque em C e refaça, ou apague o último caractere com ⌫ |

Se um problema não está na tabela, feche o app por completo e abra de novo; isso resolve a maioria dos travamentos.

## Para quem publica: GitHub Pages e atualizações

O app é composto por quatro arquivos estáticos, sem servidor, sem build e sem dependências externas.

| Arquivo | Função |
| --- | --- |
| `index.html` | O aplicativo inteiro: telas, estilos e programação |
| `manifest.json` | Nome "MacGyver", cores e ícone para a instalação como app |
| `sw.js` | Service Worker que guarda os arquivos para uso offline |
| `icon.svg` | Ícone do aplicativo |

**Publicar**

1. Crie um repositório no GitHub e envie os quatro arquivos para a raiz dele.
2. Em Settings, abra Pages, escolha "Deploy from a branch", selecione a branch `main` e a pasta `/ (root)` e salve.
3. Aguarde alguns minutos. O endereço será `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`. O GitHub Pages já usa HTTPS, exigido para a instalação e o uso offline.

**Atualizar**

1. Substitua os arquivos alterados no repositório.
2. Sempre que o `index.html` mudar, aumente o número da versão na primeira linha do `sw.js`. A versão atual é `macgyver-v4`; troque por `macgyver-v5` na próxima atualização. Sem essa troca, os aparelhos podem continuar usando a cópia antiga.
3. Nos celulares, a nova versão passa a valer depois que o app é fechado por completo e aberto duas vezes.

O ícone é um arquivo SVG. Se algum navegador não oferecer a instalação por causa do ícone, gere versões PNG de 192 e 512 pixels e aponte para elas no `manifest.json`.
