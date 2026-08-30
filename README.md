# TauScreen

**TauScreen** é um gravador de tela gratuito para Windows, desenvolvido com foco em simplicidade, praticidade e controle durante a gravação.

Ele permite gravar a tela, áudio e webcam, fazer capturas de tela, desenhar sobre a gravação, recuperar gravações temporárias e gerenciar tudo através de uma interface simples.

---

## Principais recursos

### 🎥 Gravação de tela

Grave o conteúdo da tela do Windows de forma simples e direta.

O TauScreen foi pensado para usos como:

* tutoriais;
* aulas;
* apresentações;
* gameplays;
* demonstrações de programas;
* gravação de erros e bugs;
* suporte técnico;
* criação de conteúdo.

---

## 🔊 Gravação de áudio

O TauScreen permite trabalhar com áudio durante a gravação, incluindo suporte a dispositivos de entrada e áudio utilizado na captura.

Você pode utilizar, por exemplo:

* microfone;
* áudio do computador;
* dispositivos disponíveis no Windows.

---

## 📷 Webcam

A webcam pode ser adicionada à gravação.

Antes mesmo de começar a gravar, é possível configurar:

* câmera utilizada;
* posição;
* rotação;
* espelhamento.

### Rotação

A webcam pode ser girada em:

```text
0°
90°
180°
270°
```

Quando a câmera é girada para `90°` ou `270°`, o preview ajusta automaticamente sua proporção para o formato vertical.

O TauScreen respeita a proporção original da câmera, incluindo webcams:

```text
16:9
4:3
e outras proporções
```

### Espelhamento

A webcam também pode ser espelhada horizontalmente.

Isso é útil principalmente para webcams frontais, deixando a imagem com comportamento semelhante ao de um espelho.

---

## 🪟 Mini janela da webcam

Durante a gravação, a webcam pode aparecer em uma pequena janela flutuante.

Essa janela:

* pode ser movida pela tela;
* mantém a proporção correta da câmera;
* acompanha a rotação;
* permite girar a câmera;
* permite espelhar a câmera;
* pode ser minimizada para a barra de tarefas do Windows.

A janela de preview é separada da composição final da webcam, evitando duplicação acidental no vídeo.

---

## ⏺️ Barra compacta de gravação

Durante a gravação, o TauScreen utiliza a `WinRecordingMini`, uma pequena barra flutuante para controlar a sessão.

Ela possui controles rápidos para:

* pausar;
* continuar;
* tirar print;
* abrir as ferramentas de anotação;
* finalizar a gravação;
* minimizar para a barra de tarefas.

O relógio da gravação permanece visível na própria barra.

---

## 📸 Captura de tela

O TauScreen possui uma ferramenta integrada para capturas de tela.

### Print de área

Ao utilizar o botão de captura:

1. a ferramenta de seleção é aberta;
2. você arrasta o mouse sobre a região desejada;
3. a área selecionada é salva como imagem.

As capturas recebem nomes automáticos, por exemplo:

```text
TauScreen_Captura_2026-08-30_14-32-18_125.png
```

As imagens também podem aparecer no Histórico do TauScreen.

---

## ✏️ Quadro de anotações

Durante uma gravação, é possível abrir o quadro de anotações.

Ele reúne ferramentas para auxiliar apresentações, explicações e tutoriais.

---

## ✏️ Desenho livre sobre a tela

Dentro do quadro de anotações existe a ferramenta de **Desenho livre na tela**.

Quando ativada:

* o quadro de anotações é ocultado;
* você pode desenhar diretamente sobre a tela;
* os traços aparecem durante a gravação;
* a cor selecionada no quadro é utilizada pelo lápis.

### Atalho

```text
Ctrl + Shift + D
```

Durante o modo de desenho livre, esse atalho encerra o modo de desenho.

Os rascunhos ficam ocultos ao sair do modo livre, mas não são obrigatoriamente apagados.

---

## 🧽 Borracha rápida

Durante o desenho livre:

```text
Segure Ctrl
```

O lápis é temporariamente transformado em uma borracha.

A borracha funciona por traço:

* encoste em um risco;
* o traço inteiro é removido;
* solte `Ctrl`;
* o lápis volta automaticamente.

Também estão disponíveis:

```text
Ctrl + Z
```

para desfazer o último traço.

E:

```text
Delete
```

para limpar os desenhos.

---

## 🗂️ Histórico

O TauScreen possui um Histórico integrado para facilitar o acesso às gravações e capturas recentes.

No Histórico é possível:

* visualizar gravações;
* visualizar prints;
* abrir um arquivo;
* abrir sua localização no Windows;
* remover uma entrada apenas do Histórico;
* excluir o arquivo real do computador;
* selecionar vários itens;
* selecionar tudo;
* excluir vários arquivos;
* remover vários itens do Histórico.

A exclusão de arquivos solicita confirmação antes de apagar dados do disco.

---

## ▶️ Preview no Histórico

O Histórico possui um painel de visualização ao lado da lista.

### Imagens

Capturas de tela são exibidas diretamente no preview.

### Vídeos

Vídeos podem ser reproduzidos dentro do próprio Histórico.

O preview oferece controles para:

* reproduzir;
* pausar;
* continuar;
* abrir o arquivo.

Isso permite verificar rapidamente uma gravação antes de decidir o que fazer com ela.

---

## ♻️ Recuperação de gravações temporárias

O TauScreen mantém um sistema de arquivos temporários para ajudar a recuperar gravações que não chegaram ao processo normal de salvamento.

No Histórico existe uma área específica:

```text
Arquivos temporários
```

Ela permite:

* visualizar sessões temporárias;
* selecionar uma sessão;
* selecionar várias sessões;
* selecionar tudo;
* visualizar informações da sessão;
* visualizar preview quando disponível;
* recuperar arquivos;
* excluir arquivos temporários.

---

## 💾 Recuperar temporários

Os arquivos recuperados são enviados para:

```text
Vídeos\TauScreen\Recuperados
```

Quando possível, o TauScreen tenta reconstruir automaticamente o vídeo utilizando os arquivos disponíveis da sessão.

Se algum componente estiver incompleto, o programa tenta preservar o material recuperável em vez de simplesmente descartar toda a gravação.

---

## 🗑️ Controle dos temporários

Quando o salvamento de uma gravação é cancelado, o TauScreen pergunta se o usuário deseja manter os arquivos temporários.

Você pode escolher:

### Manter

A sessão permanece disponível no Histórico para recuperação posterior.

### Excluir

Os arquivos temporários daquela gravação são descartados.

Isso evita ocupar espaço em disco com gravações que você não deseja manter.

---

## 🛡️ Recuperação de webcam

O TauScreen utiliza um formato temporário preparado para reduzir problemas caso uma gravação da webcam seja interrompida antes da finalização normal.

Arquivos inválidos são verificados antes de serem utilizados.

Se uma webcam temporária estiver corrompida, o TauScreen evita interromper completamente o salvamento da gravação principal.

---

## 📝 Nomes automáticos

As gravações recebem nomes organizados automaticamente.

Exemplo:

```text
TauScreen_Gravacao_2026-08-30_14-32-18.mp4
```

Capturas de tela:

```text
TauScreen_Captura_2026-08-30_14-32-18_125.png
```

Isso facilita a organização por data e horário.

---

# Como instalar

O TauScreen não precisa de um instalador tradicional.

### 1. Baixe a versão mais recente

Acesse a área de **Releases** deste repositório.

Baixe o arquivo `.zip` da versão desejada.

### 2. Extraia o arquivo

Não execute o TauScreen diretamente de dentro do ZIP.

Extraia todo o conteúdo para uma pasta.

### 3. Execute

Abra:

```text
INICIAR_TAUSCREEN.bat
```

Na primeira execução, o TauScreen poderá preparar automaticamente os componentes necessários.

---

# Requisitos

* Windows 64 bits;
* espaço livre para armazenar as gravações;
* microfone, caso deseje gravar sua voz;
* webcam, caso deseje utilizar captura de câmera;
* conexão com a internet durante a configuração inicial de componentes, quando necessária.

---

# FFmpeg

O TauScreen utiliza o **FFmpeg** como ferramenta externa para processamento e codificação de mídia.

O FFmpeg não é incorporado diretamente ao código do TauScreen.

Quando necessário, o programa utiliza uma versão compatível preparada para o funcionamento do sistema de gravação.

Projeto oficial:

https://ffmpeg.org/

As informações referentes às bibliotecas e componentes de terceiros utilizados pelo TauScreen estão disponíveis na distribuição.

---

# Licenças de terceiros

A versão distribuída do TauScreen contém uma pasta:

```text
Licencas/
```

e o arquivo:

```text
THIRD_PARTY_NOTICES.txt
```

Esses arquivos documentam componentes de terceiros utilizados pelo programa, incluindo quando aplicável:

* FFmpeg;
* NAudio;
* MaterialDesignInXamlToolkit;
* Material Design Icons.

Cada projeto permanece sujeito à sua respectiva licença.

---

# Segurança das gravações

Antes de uma gravação importante, recomenda-se:

* verificar o dispositivo de áudio;
* verificar a webcam;
* conferir o espaço livre em disco;
* fazer uma pequena gravação de teste;
* não encerrar o TauScreen à força durante o salvamento.

Caso uma gravação seja interrompida, consulte:

```text
Histórico → Arquivos temporários
```

antes de apagar os arquivos temporários.

---

# Contribuições

Sugestões, relatórios de problemas e melhorias podem ser enviados através da área de **Issues** do repositório.

Pull Requests também podem ser utilizados para contribuir com o desenvolvimento quando habilitados no projeto.

---

# TauScreen

**Gravação de tela, áudio, webcam, capturas e anotações em uma ferramenta simples para Windows.**
