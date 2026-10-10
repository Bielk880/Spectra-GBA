<p align="center">
  <img src="logo.png" width="120" alt="Spectra GBA">
</p>

<h1 align="center">Spectra GBA</h1>

<p align="center">
  Emulador de Game Boy Advance para Android, feito para jogar no celular com conforto.
</p>

<p align="center">
  <a href="https://github.com/Bielk880/Spectra-GBA/releases/latest"><img src="https://img.shields.io/badge/Baixar-64%20bits-8b5cf6?style=for-the-badge" alt="Baixar a última versão (64 bits)"></a>
  &nbsp;
  <a href="https://github.com/Bielk880/Spectra-GBA/releases"><img src="https://img.shields.io/badge/Baixar-32%20bits-22d3ee?style=for-the-badge" alt="Baixar a última versão (32 bits)"></a>
</p>

<p align="center">
  Não sabe qual baixar? Tente primeiro a de 64 bits. Se o celular disser que não é compatível, use a de 32 bits.
  <br>
  <a href="https://github.com/Bielk880/Spectra-GBA/issues">Relatar um problema</a>
</p>

<p align="center">
  <img src="https://img.shields.io/github/v/release/Bielk880/Spectra-GBA?label=vers%C3%A3o&color=8b5cf6">
  <img src="https://img.shields.io/badge/Android-7.0%2B-22d3ee">
  <img src="https://img.shields.io/github/downloads/Bielk880/Spectra-GBA/total?label=downloads&color=ec4899">
</p>

---

## Capturas de tela

<p align="center">
  <img src="print1.png" width="24%">
  <img src="print2.png" width="24%">
  <img src="print3.png" width="24%">
  <img src="print4.png" width="24%">
</p>

<p align="center">
  <img src="banner.png" width="98%">
</p>

## Sobre o projeto

O Spectra GBA nasceu da vontade de ter um emulador simples de usar, com visual caprichado e as funções que realmente fazem falta no dia a dia. Por baixo, ele usa o mGBA, um dos núcleos de emulação mais precisos que existem.

## Funções

**Jogo**
- Modo Link: dois jogos rodando ao mesmo tempo no mesmo celular, ligados por um cabo virtual, para trocar e batalhar
- Save states com miniatura, salvamento automático e "retomar de onde parou"
- Save states também no Modo Link: salva os dois jogos juntos, até no meio de uma troca ou batalha
- Rewind para voltar alguns segundos no tempo
- Velocidade de 0.2x (câmera lenta) até 16x
- Cheats nos formatos GameShark, Action Replay e CodeBreaker
- Conquistas do RetroAchievements

**Controles**
- Cada botão e cada atalho com posição e tamanho próprios, e a tela do jogo também pode ser movida e redimensionada
- 7 estilos de botão, entre eles Vidro, Neon, Relevo 3D e Retrô, com cor ajustável
- Direcional em setas, cruz clássica, joystick ou joystick RGB
- Barra de atalhos que pode ser movida, redimensionada ou escondida
- Suporte a controle Bluetooth, com mapeamento de botões

**Visual**
- Filtros em duas camadas, que podem ser combinados: um de tela (LCD, Scanlines, CRT, Suave, Desenho) e um de cores (Cores GBA, Cinza, Verde GB, Pocket, Sépia, Vívido, Conforto)
- 12 fundos para a tela do jogo, além de cor sólida ou imagem da sua galeria
- Temas de cores, cartões e menus pretos ou transparentes, e tela cheia ou ampliada no modo horizontal

**Saves e biblioteca**
- Saves .sav compatíveis com PKHeX, com opção de exportar e importar
- Backup dos saves no Google Drive
- Biblioteca com busca, capas e tempo de jogo
- Aviso automático quando sai uma versão nova
- Tela de início original do GBA, usando a sua própria BIOS (opcional)

## Requisitos

- Android 7.0 ou superior
- Funciona em celulares de 64 bits e de 32 bits.

## Instalação

1. Baixe o arquivo `.apk` pelos botões lá em cima (64 ou 32 bits). Na página da versão, o arquivo fica no fim, em **Assets**
2. Abra o arquivo e permita a instalação, se o Android pedir
3. No app, toque em **Sincronizar** para encontrar seus jogos ou em **Adicionar** para escolher um arquivo

Para atualizar, é só instalar a versão nova por cima. Seus jogos, saves e configurações continuam. A partir da versão 2.6, o próprio app avisa quando houver atualização.

## Perguntas frequentes

**O app vem com jogos?**
Não. O Spectra é só o emulador. Use cópias de jogos que você possui.

**Preciso da BIOS do GBA?**
Não. Ela é opcional e serve para exibir a tela de início original do console.

**Meus saves são compatíveis com outros emuladores?**
Sim. O formato .sav é o mesmo usado pela maioria dos emuladores e pelo PKHeX.

**Como funciona o Modo Link?**
No menu da biblioteca, escolha Modo Link e selecione dois jogos. Os dois rodam juntos, e você alterna entre eles tocando no nome do jogador. Para trocar ou batalhar, use a opção de conexão por cabo dentro de cada jogo. No menu do Modo Link também dá para salvar e carregar estados dos dois jogos de uma vez.

## Encontrou um problema?

Abra uma [Issue](https://github.com/Bielk880/Spectra-GBA/issues) contando o que aconteceu, o modelo do seu celular e o jogo. Sugestões também são bem-vindas.

## Créditos

- Emulação: [mGBA](https://mgba.io), de Vicki Pfau e colaboradores (Mozilla Public License 2.0)
- Conquistas: [rcheevos](https://github.com/RetroAchievements/rcheevos), do RetroAchievements (MIT License)

O Spectra foi desenvolvido com auxílio de IA na programação. A direção do projeto, os testes e os ajustes foram feitos por mim, com base nas sugestões da comunidade.

O jogo que aparece nas capturas é o Spectra Ghost, um jogo de demonstração feito para o projeto.

## Código-fonte do mGBA

O Spectra usa o mGBA, que é de código aberto (Mozilla Public License 2.0). O código do mGBA usado no app, com as mudanças feitas para o Modo Link, está em [spectra-mgba-source.zip](spectra-mgba-source.zip). Dentro dele, o arquivo `LEIA-ME.md` explica o que foi alterado.

## Licença e privacidade

O Spectra GBA é distribuído gratuitamente, com todos os direitos reservados (exceto as partes de terceiros, que seguem as próprias licenças). Veja a [licença](LICENSE) e a [política de privacidade](PRIVACY.md).

## Aviso legal

O Spectra GBA não inclui jogos nem arquivos de BIOS e não apoia a pirataria.
Game Boy Advance é marca registrada da Nintendo. Este projeto não tem ligação nem aprovação da Nintendo.
