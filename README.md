# Um exemplo cliente/servidor - Kotlin Android / NestJS (2026)

Este repositório corresponde ao curso **"Um exemplo cliente/servidor - Kotlin Android / NestJS (2026)"**, publicado em:

**https://stahe.github.io/br-kotlin-android-nestjs-oct-2026/**

## Visão geral

Este documento adapta o aplicativo didático **RdvMedecins** (um aplicativo de agendamento de consultas médicas), já abordado nos cursos de Angular, React, Vue.js e Flutter, para um aplicativo Android nativo. Aqui ele apresenta uma versão **Android**: um cliente escrito em **Kotlin** com **Jetpack Compose** (Material 3), que se apoia em um servidor **NestJS** (TypeScript) que expõe uma API JSON protegida por autenticação JWT (papéis ADMIN / USER).

Este documento oferece um guia passo a passo que segue a progressão do curso [Um exemplo cliente/servidor - Flutter / NestJS (2026)](https://stahe.github.io/br-flutter-nestjs-sept-2026/), do qual aproveita o servidor, o banco de dados e a arquitetura do cliente: cada conceito do Jetpack Compose é relacionado ao seu equivalente no Flutter. Os fundamentos da linguagem Kotlin são abordados no [curso de Kotlin](https://stahe.github.io/br-kotlin-oct-2026/).

O curso aborda:

- a configuração do ambiente de desenvolvimento (Android Studio, SDK do Android, Gradle, criação de um projeto Compose, emulador e celular Android);
- a instalação e a execução do servidor NestJS do aplicativo (banco de dados MySQL, configuração, testes com um navegador e com o Postman);
- uma introdução ao Android e ao Jetpack Compose (activities, funções `@Composable`, estado e recomposição, `CompositionLocal`, corrotinas, ciclo de vida e `ViewModel`);
- um passo a passo detalhado, arquivo por arquivo, do cliente Kotlin do aplicativo RdvMedecins (OkHttp, kotlinx.serialization, SharedPreferences, Material 3);
- a execução do aplicativo em um emulador e em um celular, tratando das armadilhas específicas do mobile (endereço do servidor, `adb reverse`, tráfego HTTP não criptografado, rotação de tela, telas estreitas), a geração de um APK e uma visão geral do Kotlin Multiplatform;
- uma conclusão sobre o que foi construído e sugestões para explorações futuras.

## Autores

- **Autora principal:** IA Claude (Anthropic)
- **Revisor:** [Serge Tahé](https://stahe.github.io)
