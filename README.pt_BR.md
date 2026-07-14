# Mouse Synchronization

🌐 [English](README.md) · [Tiếng Việt](README.vi.md) · [বাংলা](README.bn.md) · [हिन्दी](README.hi.md) · **Português (BR)** · [Русский](README.ru.md) · [Türkçe](README.tr.md) · [اردو](README.ur.md) · [简体中文](README.zh_CN.md)

**Controle várias janelas ao mesmo tempo com um único mouse.**

O Mouse Synchronization permite escolher uma janela como a "líder" e copia tudo o que você faz nela — cliques, rolagem e arrastar — para quantas outras janelas você quiser, todas ao mesmo tempo. É perfeito quando você tem várias cópias do mesmo aplicativo abertas e está cansado de repetir a mesma ação em cada uma.

Feito por **Duck Martians** · [duckmartians.info](https://duckmartians.info)

---

## Primeiros passos

1. Abra as janelas ou aplicativos que você quer controlar (por exemplo, várias cópias do mesmo programa).
2. Abra o **Mouse Synchronization** (execute o aplicativo).
3. Siga os 5 passos abaixo.

É só isso — sem configuração, sem conta.

---

## Use em 5 passos

1. **Encontre suas janelas.** O painel da esquerda, **Janelas abertas**, mostra tudo o que está
   aberto no momento. Suas janelas de destino estão ali.
2. **Adicione-as à lista de sincronização.** Clique no **➕** verde ao lado de uma janela (ou selecione
   várias e clique em **Adicionar →**). Elas vão para o painel da direita, **Lista de sincronização**.
3. **Escolha a líder.** Na Lista de sincronização, clique na **estrela ☆** ao lado da janela que
   você quer usar para controlar. Ela fica **dourada ★** — essa passa a ser a sua janela principal.
4. **Clique em Iniciar.** Clique no botão verde **Iniciar** (ou pressione **Ctrl + 1**).
5. **Use sua janela líder.** Clique, role ou clique e arraste dentro da janela principal,
   e todas as outras janelas da lista fazem exatamente a mesma coisa no mesmo instante.

Para parar, clique em **Parar sincronização** (ou **Ctrl + 2**). Para uma pausa rápida sem parar,
clique em **Pausar**.

> Você precisa ter uma janela principal escolhida **e pelo menos 2 janelas** na lista de sincronização antes que o Iniciar funcione.

---

## O que cada parte da tela faz

### Painel da esquerda — Janelas abertas
Uma lista ao vivo de todas as janelas abertas no seu computador.
- **➕** — adiciona esta janela à lista de sincronização.
- **👁 (olho)** — traz esta janela para a frente para você poder vê-la.
- **Caixa de busca** — digite parte do nome de uma janela para filtrar a lista (por exemplo, digite
  o nome de um programa para esconder todo o resto).
- **Adicionar todas as correspondentes** — adiciona, em um clique, todas as janelas que correspondem à sua busca. Ótimo
  quando você tem mais de 10 janelas para adicionar. (Este botão só funciona depois que você digita algo na caixa de busca.)
- **Somente a Área de Trabalho atual** — esconde as janelas que ficam nas suas outras áreas de trabalho virtuais.

### Caixa "Abrir mais janelas"
Quer mais cópias de um programa?
1. Clique em uma janela na lista **Janelas abertas**.
2. Defina quantas cópias você quer.
3. Clique em **Abrir mais**.

O aplicativo encontra o programa por trás daquela janela e abre cópias extras para você.
(Alguns programas só permitem que uma cópia deles rode ao mesmo tempo — esses simplesmente vão fechar as
cópias extras. Essa é uma regra do programa, não um problema aqui.)

### Coluna do meio — ações
- **Adicionar → / ← Remover / Remover tudo** — mova janelas para dentro e para fora da lista de sincronização.
- **Atualizar** — verifica novamente as janelas abertas (use se uma janela estiver faltando na lista).
- **Organizar** — arruma automaticamente suas janelas de sincronização em uma grade organizada. Escolha qual
  monitor (ou monitores) usar com as caixas de seleção em **Selecionar monitor** e clique em Organizar.
- **Selecionar monitor** — marque as telas nas quais você quer organizar as janelas. A **estrela**
  indica sua tela "principal" (isso é apenas um rótulo dentro do aplicativo — ele **não** altera
  as suas configurações do Windows).

### Painel da direita — Lista de sincronização
As janelas que vão seguir a sua líder.
- **Estrela ★** — escolha a janela líder (principal). Só uma pode ser a líder.
- **👁 (olho)** — traz essa janela para a frente.
- **➖** — remove esta janela da lista.

### Barra inferior — controles
- **Iniciar / Pausar / Parar** — inicie, pause ou pare a sincronização.
- As pequenas caixas embaixo de cada botão são os **atalhos de teclado** (veja abaixo).
- **Sincronizar pela proporção da janela** — **ative** esta opção se suas janelas tiverem tamanhos diferentes ou estiverem em
  posições diferentes; assim ela combina as ações pela posição *relativa* em vez das coordenadas exatas.
  Deixe **desativada** se todas as suas janelas tiverem o mesmo tamanho e estiverem alinhadas.
- **🏠 Botão Início** — abre o site da Duck Martians.
- **🌐 Botão de idioma** — muda o idioma do aplicativo.

---

## Atalhos de teclado

Você pode controlar tudo sem tocar nos botões:

| Ação | Atalho padrão |
|--------|------------------|
| Iniciar  | **Ctrl + 1** |
| Parar   | **Ctrl + 2** |
| Pausar / Retomar | **Alt + 1** |

**Mudar um atalho:** clique em uma caixa de atalho, digite as teclas que você quer (por exemplo,
`Ctrl` na primeira caixa e `F5` na segunda) e clique fora. As caixas de atalho ficam
**bloqueadas durante a sincronização** — pare primeiro se quiser alterá-las.

Seus atalhos são **lembrados** na próxima vez que você abrir o aplicativo.

---

## O selo de status flutuante

Quando a sincronização começa, um pequeno selo aparece no canto da sua tela:
- **Verde** = a sincronização está rodando.
- **Âmbar** = pausada.

Você pode **clicar no selo** para pausar ou retomar — útil quando suas outras janelas estão
cobrindo o aplicativo. O selo desaparece quando você clica em Parar.

---

## Rodando várias cópias da ferramenta

Você pode abrir o Mouse Synchronization mais de uma vez (cada cópia recebe seu próprio número, como
"Instância 1", "Instância 2"). Cada cópia tem seu **próprio** atalho de Pausar (Alt + o número dela),
para que você possa pausá-las de forma independente.

---

## Bom saber

- **O que é copiado:** clique com o botão esquerdo, clique com o botão direito, clique com o botão do meio, rolagem e
  clicar e arrastar (segurar o botão esquerdo e mover) — tudo feito dentro da janela principal.
- **Os nomes das janelas mudam de propósito:** enquanto uma janela está na lista de sincronização, o aplicativo adiciona um
  número pequeno como `[1]`, `[2]` ao título dela para você conseguir diferenciá-las. Os nomes originais
  voltam quando você as remove ou fecha o aplicativo.
- **Direitos de administrador:** o aplicativo funciona normalmente sem eles. Mas se uma janela que você quer
  controlar estiver rodando "como administrador", o Windows impede que um aplicativo comum
  a manipule — nesse caso, execute o Mouse Synchronization como administrador também
  (clique com o botão direito no aplicativo → **Executar como administrador**).

---

## Idioma e configurações salvas

- O aplicativo oferece suporte a **9 idiomas**: English, Tiếng Việt, বাংলা, हिन्दी, Português (Brasil),
  Русский, Türkçe, اردو e 简体中文. Clique no **🌐 botão de idioma** para trocar — a mudança é
  instantânea, sem precisar reiniciar.
- Seu **idioma** e seus **atalhos de teclado** são salvos automaticamente, então o aplicativo abre
  do jeito que você deixou na próxima vez.

---

## Solução de problemas

**O Iniciar não faz nada / mostra um aviso.**
Verifique se você escolheu uma janela principal (estrela dourada) e adicionou pelo menos 2 janelas à
lista de sincronização.

**Uma janela que eu quero não está na lista.**
Clique em **Atualizar**. Se ela estiver em outra área de trabalho virtual, desmarque **Somente a Área de Trabalho atual**.

**As outras janelas não reagem quando eu clico.**
A janela que está *de fato* sendo clicada precisa ser a sua líder (a que tem a estrela
dourada). Verifique também se a sincronização está rodando (selo verde no canto). Se a sua janela
de destino roda "como administrador", execute este aplicativo como administrador também.

**As janelas não estão alinhadas do jeito que eu espero.**
Se elas tiverem tamanhos diferentes, ative **Sincronizar pela proporção da janela**. Para organizá-las em uma grade,
marque os monitores em **Selecionar monitor** e clique em **Organizar**.

---

## Sobre

Mouse Synchronization · por **Duck Martians**
[duckmartians.info](https://duckmartians.info)
