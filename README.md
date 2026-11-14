# FF Painel de Treino — Moto G35 5G

Projeto Android Studio em Kotlin para um painel flutuante auxiliar de treino.

## O que faz
- Abre um painel flutuante movível.
- Mostra lembretes de treino, sensibilidade e organização de HUD para 4 dedos.
- Inclui cronômetro de treino de precisão de 60 segundos.
- Pode ser encerrado pelo botão no painel ou pela notificação.

## Limites
Este projeto não modifica o Free Fire, não injeta código no jogo, não automatiza toques,
não oferece aimbot, macros, anti-ban, wallhack ou qualquer vantagem escondida.
Use somente se as regras do campeonato permitirem sobreposições.

## Como abrir
1. Extraia o ZIP.
2. Abra a pasta `FF_Painel_Treino_Moto_G35` no Android Studio.
3. Aguarde a sincronização do Gradle.
4. Conecte o Moto G35 5G com depuração USB ou use um emulador.
5. Execute o app.
6. Toque em **Ativar painel flutuante** e conceda a permissão de sobreposição do Android.
7. Para fechar, use **Fechar painel** ou **Encerrar** na notificação.

## Observação
O Android pode pedir permissão para notificações dependendo da versão e das configurações.
A disponibilidade de serviços em primeiro plano e sobreposições pode variar conforme a versão do Android.

## Gerar APK sem Android Studio (pelo celular)
Este projeto inclui um workflow do GitHub Actions.
1. Extraia o ZIP no celular.
2. No navegador, entre em github.com e crie um repositório vazio chamado `FF-Painel-Treino`.
3. Envie o conteúdo da pasta do projeto para a raiz do repositório, incluindo a pasta oculta `.github/workflows`.
4. Abra a aba **Actions** do repositório e selecione **Gerar APK Android**.
5. Toque em **Run workflow** (ou aguarde a execução iniciada pelo envio para `main`).
6. Quando aparecer como concluído, abra a execução e baixe o arquivo em **Artifacts**.
7. Extraia o arquivo baixado e toque em `app-debug.apk` para instalar. O Android poderá pedir autorização para instalar apps dessa fonte.

Se a pasta `.github` não aparecer no seletor de arquivos do celular, habilite a opção de mostrar arquivos ocultos no gerenciador ou use a opção de upload de pasta/arquivos do navegador. O workflow precisa estar exatamente em `.github/workflows/android.yml`.
