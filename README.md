# Intent

App Android para praticar o uso de **Intents**, feito em **Kotlin**.

> Projeto desenvolvido na faculdade, na disciplina de Programação para Dispositivos Móveis (PDM), em 2024.

## O que o app demonstra

- **Intent explícita:** abre uma segunda tela, envia um texto para ela e recebe o texto editado de volta (Activity Result API)
- **Intents implícitas**, pelo menu da toolbar:
  - abrir um endereço no navegador
  - escolher qual navegador usar (`ACTION_CHOOSER`)
  - abrir o discador com um número (`ACTION_DIAL`)
  - fazer uma ligação (`ACTION_CALL`), pedindo a permissão em tempo de execução
  - escolher uma imagem da galeria e abri-la (`ACTION_PICK`)

## Tecnologias

- Kotlin
- Android SDK (mínimo API 26)
- View Binding
- Activity Result API e permissões em tempo de execução

## Como rodar

1. Clone o repositório e abra no Android Studio.
2. Rode o app num emulador ou celular com Android 8.0 ou superior.
