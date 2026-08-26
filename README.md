# Corrida pela Liberdade Financeira — Android

Projeto Android nativo que empacota o jogo HTML/JavaScript em um aplicativo para celular.

## Estado
- Versão: 1.0.0
- Target SDK: 36 (Android 16), alinhado ao requisito do Google Play a partir de 31/08/2026.
- Orientação: retrato.
- Gameplay: endless runner, dificuldade progressiva e pulo alto.
- Monetização: preparada para receber AdMob em uma próxima etapa; nenhum anúncio está ativo nesta versão.

## Build
Abra esta pasta no Android Studio com o Android SDK 36 instalado e sincronize o Gradle.
Depois use Build > Generate Signed App Bundle / APK > Android App Bundle.

## Publicação
O Google Play exige Android App Bundle (AAB) para novos apps. O nome do pacote `br.com.liberdadefinanceira.corrida` deve ser tratado como permanente; escolha outro antes da primeira publicação se quiser um identificador diferente.

Antes de produção, configure:
1. assinatura do app;
2. ícone final e screenshots;
3. política de privacidade e Data Safety;
4. conta AdMob, se quiser anúncios;
5. testes exigidos pelo Play Console.
