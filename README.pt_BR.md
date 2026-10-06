<h1 align="center">Mouse Synchronization</h1>

<p align="center"><b>Controle várias janelas ao mesmo tempo com um único mouse - clique, role e arraste em uma janela líder, e todas as outras janelas da lista fazem exatamente o mesmo, no mesmo instante.</b></p>

<p align="center">
  <a href="README.md">English</a> ·
  <a href="README.vi.md">Tiếng Việt</a> ·
  <a href="README.bn.md">বাংলা</a> ·
  <a href="README.hi.md">हिन्दी</a> ·
  <b>Português (BR)</b> ·
  <a href="README.ru.md">Русский</a> ·
  <a href="README.tr.md">Türkçe</a> ·
  <a href="README.ur.md">اردو</a> ·
  <a href="README.zh_CN.md">简体中文</a>
</p>

<p align="center">
  <a href="https://github.com/duckmartians/Mouse-Synchronization/releases/latest"><img alt="Baixar para Windows" src="https://img.shields.io/badge/Baixar-Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white"></a>
</p>

---

## Instalação

### Passo 1 - Baixar

Baixe a versão mais recente em **[Releases](https://github.com/duckmartians/Mouse-Synchronization/releases/latest)**:

| Seu computador | Download | Observações |
|---|---|---|
| 🪟 **Windows** | [Windows (.zip)](https://github.com/duckmartians/Mouse-Synchronization/releases/latest) | O arquivo se chama [`Mouse-Synchronization_v<versão>.zip`](https://github.com/duckmartians/Mouse-Synchronization/releases/latest). Não há versão para macOS. |

### Passo 2 - Descompactar e executar

<details open>
<summary><b>🪟 No Windows</b></summary>

1. **Descompacte** o arquivo `.zip` baixado em qualquer pasta (clique com o botão direito → **Extrair Tudo…**). Não há instalador.
2. Abra a pasta extraída e execute **`Mouse Synchronization.exe`**.
3. Se aparecer **"O Windows protegeu o computador"** (SmartScreen): clique em **Mais informações** → **Executar assim mesmo**. *(O app não é assinado com um certificado da Microsoft, por isso pode ser sinalizado - não é vírus.)*
4. Mantenha a pasta inteira junta - o `.exe` precisa dos arquivos ao lado dele. Para remover o app, basta excluir a pasta.

</details>

### Passo 3 - Grátis, sem conta

O Mouse Synchronization é **gratuito**: sem conta, sem chave de ativação, sem anúncios. Não precisa de direitos de administrador para janelas normais (veja a seção Solução de problemas abaixo para janelas executadas como administrador).

---

## Primeira execução

1. **Abra as janelas que você quer controlar** - por exemplo, várias cópias do mesmo programa.
2. **Execute o Mouse Synchronization.** O painel esquerdo, **Janelas abertas**, lista tudo o que está aberto.
3. **Adicione-as à lista de sincronização.** Clique no **➕** verde ao lado de uma janela (ou selecione várias e pressione **Adicionar →**). Elas vão para o painel direito, **Lista de sincronização**. São necessárias **pelo menos 2 janelas**.
4. **Escolha a líder.** Na Lista de sincronização, clique na **estrela ☆** ao lado da janela pela qual você quer controlar. Ela fica **dourada ★** - essa é a sua janela principal.
5. **Pressione Iniciar** (ou **Ctrl + 1**).
6. **Use a janela líder.** Clique, role ou clique e arraste dentro dela, e todas as outras janelas da lista fazem o mesmo no mesmo instante.

Para parar, clique em **Parar sincronização** (ou **Ctrl + 2**). Para uma pausa rápida sem parar, pressione **Pausar** (**Alt + 1**).

---

## Recursos

<img width="1100" alt="Mouse Synchronization" src="docs/screenshots/en/main.png" />
<img width="1919" height="1032" alt="Mouse Synchronization" src="https://github.com/user-attachments/assets/c93fee4f-a696-451e-894b-94fe3312fd58" />

- **Um mouse, várias janelas** - cliques esquerdo, direito e do meio, rolagem e clicar e arrastar dentro da janela líder são enviados ao mesmo tempo para todas as janelas da Lista de sincronização. Só o mouse é sincronizado, não o teclado.
- **Sincronizar pela proporção da janela** - quando as janelas têm tamanhos ou posições diferentes, as ações são casadas pela posição *relativa* em vez de coordenadas exatas.
- **Encontre e adicione janelas rápido** - lista de janelas ao vivo com caixa de busca, **Adicionar correspondentes** para um lote inteiro de uma vez e um filtro pela área de trabalho virtual atual.
- **Organizar em grade** - arruma suas janelas sincronizadas em uma grade uniforme nos monitores que você escolher.
- **Abrir mais janelas** - abre de 1 a 20 cópias extras do programa por trás de uma janela.
- **Atalhos personalizáveis** - Iniciar, Parar e Pausar / Retomar, lembrados entre as sessões.
- **Selo de status flutuante** - verde ao sincronizar, âmbar quando pausado; clique nele para pausar ou retomar.
- **Execute várias cópias da ferramenta** - cada cópia tem seu próprio número e seu próprio atalho de Pausa.
- **9 idiomas** - troque na hora pelo botão 🌐, sem reiniciar.

---

## A janela principal

### 🪟 Painel esquerdo - Janelas abertas

Uma lista ao vivo de todas as janelas abertas no seu computador.
- **➕** - adiciona esta janela à lista de sincronização.
- **👁** - traz esta janela para a frente para você vê-la.
- **Caixa de busca** - digite parte do nome de uma janela para filtrar a lista.
- **Adicionar correspondentes** - adiciona com um clique todas as janelas que correspondem à busca (funciona depois que você digita algo na caixa de busca). Ótimo quando há mais de 10 janelas para adicionar.
- **Apenas a Área de Trabalho atual** - oculta as janelas que estão em outras áreas de trabalho virtuais.

### ➕ Abrir mais janelas

Quer mais cópias de um programa? Clique em uma janela na lista **Janelas abertas**, defina o **Nº de janelas** (1-20) e clique em **Abrir mais**. O app encontra o programa por trás daquela janela e abre cópias extras. Alguns programas só permitem uma cópia de si mesmos - eles fecham as extras sozinhos; é uma regra do programa, não um bug.

### ↔️ Coluna do meio - ações

- **Adicionar → / ← Remover / Remover tudo** - move janelas para dentro e para fora da lista de sincronização.
- **Atualizar** - procura novamente as janelas abertas (use se uma janela estiver faltando).
- **Organizar** - arruma as janelas sincronizadas em uma grade uniforme nos monitores marcados em **Selecionar monitor**.
- **Selecionar monitor** - marque as telas onde organizar as janelas. A **estrela** indica sua tela "principal"; é apenas um rótulo dentro do app e **não** altera as configurações do Windows.

### ⭐ Painel direito - Lista de sincronização

As janelas que vão seguir a líder.
- **Estrela ★** - escolhe a janela líder (principal). Apenas uma janela pode ser a líder.
- **👁** - traz essa janela para a frente.
- **➖** - remove esta janela da lista.

Enquanto uma janela está na lista de sincronização, o app acrescenta um pequeno número como `[1]`, `[2]` ao título para você diferenciá-las. Os títulos originais voltam quando você remove a janela ou fecha o app.

### ▶️ Barra inferior - controles

- **Iniciar / Pausar / Parar sincronização** - inicia, pausa ou para a sincronização. As caixinhas abaixo de cada botão são o atalho de teclado dele.
- **Sincronizar pela proporção da janela** - **ative** se suas janelas têm tamanhos ou posições diferentes; deixe **desativado** se todas têm o mesmo tamanho e estão alinhadas.
- **🏠** - abre o site da Duck Martians ([duckmartians.info](https://duckmartians.info)).
- **🌐** - muda o idioma do app (English, Tiếng Việt, বাংলা, हिन्दी, Português (Brasil), Русский, Türkçe, اردو, 简体中文).

---

## Atalhos de teclado

| Ação | Atalho padrão |
|---|---|
| Iniciar | **Ctrl + 1** |
| Parar | **Ctrl + 2** |
| Pausar / Retomar | **Alt + 1** |

**Mudar um atalho:** clique em uma caixa de atalho, digite as teclas desejadas (por exemplo `Ctrl` na primeira caixa e `F5` na segunda) e clique fora. As caixas de atalho ficam **bloqueadas durante a sincronização** - pare primeiro para alterá-las. Seus atalhos são lembrados na próxima vez que você abrir o app.

## Selo de status flutuante

Quando a sincronização começa, um pequeno selo aparece no canto da tela: **verde** = sincronizando, **âmbar** = pausado. **Clique no selo** para pausar ou retomar - útil quando outras janelas cobrem o app. Ele some quando você pressiona Parar.

## Executar várias cópias da ferramenta

Você pode abrir o Mouse Synchronization mais de uma vez. Cada cópia recebe seu próprio número ("Instância 1", "Instância 2"…) mostrado no título e no botão Pausar, e seu próprio atalho de Pausa padrão (**Alt + o número dela**), para que você possa pausá-las de forma independente.

---

## Onde ficam seus dados

| O quê | Onde |
|---|---|
| Idioma e atalhos de teclado | `%APPDATA%\Mouse Synchronization\settings.ini` |

Nada mais é salvo, e o app não envia nada para lugar nenhum - as ações do mouse vão direto para as janelas do seu próprio computador.

---

## Solução de problemas

**Iniciar não faz nada / mostra um aviso** - escolha uma janela principal (estrela dourada ★) e adicione pelo menos 2 janelas à lista de sincronização.

**Uma janela que eu quero não está na lista** - clique em **Atualizar**. Se ela estiver em outra área de trabalho virtual, desmarque **Apenas a Área de Trabalho atual**.

**As outras janelas não reagem quando eu clico** - você precisa agir dentro da janela líder (estrela dourada) enquanto a sincronização está rodando (selo verde). Se uma janela de destino roda "como administrador", o Windows impede que apps normais a controlem - clique com o botão direito no Mouse Synchronization → **Executar como administrador**.

**As janelas não estão alinhadas como eu esperava** - se têm tamanhos diferentes, ative **Sincronizar pela proporção da janela**. Para organizá-las em grade, marque os monitores em **Selecionar monitor** e clique em **Organizar**.

**"Abrir mais" abre uma cópia que fecha na hora** - esse programa só permite uma cópia de si mesmo.

**O Windows bloqueia com "O Windows protegeu o computador"** - clique em **Mais informações → Executar assim mesmo**. O app não é assinado com um certificado da Microsoft - não é vírus.
