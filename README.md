# Beam

Beam é um espaço pessoal para usar **Codex** e **Claude Code** no computador e continuar as mesmas conversas pelo celular. Esta página só distribui o app; as versões ficam em [Releases](../../releases).

## Antes de instalar

- **Codex** e/ou **Claude Code** já instalados e com login feito no seu computador. O Beam usa esses programas; ele não faz login por você.
- Mac com Apple Silicon (M1 ou mais novo) e macOS 11 ou mais novo, **ou** Ubuntu 24.04 ou 26.04 em PC Intel/AMD.

## Mac

1. Em [Releases](../../releases/latest), baixe `Beam-<versão>-macos-arm64.dmg`.
2. Abra o arquivo e arraste o **Beam** para **Aplicativos**.
3. Abra o Beam uma vez pela pasta Aplicativos. O macOS avisa que não pode verificar o app: clique em **OK**.
4. Abra **Ajustes do Sistema → Privacidade e Segurança**, role até a mensagem sobre o Beam e clique em **Abrir Mesmo Assim**.
5. Confirme com **Abrir** (e sua senha, se pedir).

Isso só é necessário na primeira vez. As próximas versões chegam sozinhas: o Beam avisa "Atualização pronta · Reiniciar" e você escolhe quando reiniciar. Não desative o Gatekeeper nem use comandos para remover a quarentena.

## Ubuntu

1. Em [Releases](../../releases/latest), baixe `beam_<versão>_amd64.deb`.
2. No Terminal, na pasta do arquivo:

   ```sh
   sudo apt install ./beam_<versão>_amd64.deb
   ```

3. Abra o **Beam** pelo menu de aplicativos.

As próximas versões chegam sozinhas; ao clicar em **Reiniciar**, o Ubuntu pede sua senha para instalar.

## Conectar o celular

1. No computador: **Configurações → Celular** mostra um QR.
2. **iPhone:**
   1. Leia o QR com a câmera e abra o link no **Safari**.
   2. Toque em **Compartilhar → Adicionar à Tela de Início**.
   3. Abra o Beam pelo ícone e, dentro do app, leia o QR de novo ou cole o link do computador.

   O pareamento precisa ser feito no app instalado, porque o iPhone guarda os dados do Safari separados.
3. **Android:** leia o QR ou abra o link no navegador.

O computador precisa estar ligado e com o Beam aberto (ou com a janela fechada, mas sem encerrar) para o celular funcionar.

## Se algo falhar

- **"O Beam não pode ser aberto"** no Mac: refaça os passos 3 a 5.
- **O Beam abre de dentro do arquivo baixado** e diz que não pode se atualizar: arraste-o para Aplicativos e abra de lá.
- **Uma atualização não abriu**: o Beam volta sozinho para a versão anterior e avisa. No Ubuntu, se ele não conseguir voltar, a mensagem mostra o comando para reinstalar a versão anterior.
- Suas conversas ficam no seu computador e são mantidas em atualizações e reinstalações.
