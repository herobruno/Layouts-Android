# Layouts-Android & Login Flow 📱

Aplicativo Android desenvolvido em Kotlin para demonstrar e comparar os principais sistemas de gerenciamento de layout em Android (XML Views), integrado com um fluxo de Autenticação/Login.

---

## 🚀 Sobre o Projeto

Este projeto tem como objetivo servir de guia e referência prática para o uso de diferentes layouts no desenvolvimento Android nativo. Além disso, ele implementa um fluxo inicial de **Login** (E-mail e Senha) que valida os dados inseridos pelo usuário antes de redirecionar para a tela de comparativo de layouts.

Cada layout foi redesenhado com um caso de uso real e distinto para evidenciar as forças e características de cada ViewGroup:
- **LinearLayout:** Tela de Configurações / Preferências.
- **RelativeLayout:** Card de Produto com Banner e Badges sobrepostas.
- **TableLayout:** Extrato Financeiro / Tabela de Despesas.
- **ConstraintLayout:** Postagem Social / Perfil com hierarquia plana.

---

## 🛠️ Layouts e Telas Demonstradas

1. **Tela de Login (`activity_login.xml` / `MainActivity.kt`)**
   - Tela inicial solicitando E-mail e Senha, com validação de campos e navegação para o comparativo.

2. **ConstraintLayout (`activity_constraint.xml`)**
   - Layout flexível e recomendado para interfaces complexas sem aninhamento excessivo.

3. **LinearLayout (`activity_linear_demo.xml`)**
   - Organiza os elementos filhos em uma única direção (vertical ou horizontal).

4. **RelativeLayout (`activity_relative.xml`)**
   - Permite posicionar elementos filhos em posições relativas uns aos outros ou ao container pai.

5. **TableLayout (`activity_table.xml`)**
   - Organiza os elementos em linhas (`TableRow`) e colunas para dados tabulares estritos.

---

## 📂 Estrutura do Projeto

```text
app/
├── src/
│   └── main/
│       ├── java/com/example/login/
│       │   ├── MainActivity.kt (Tela de Login)
│       │   ├── ComparisonActivity.kt (Tela de Comparativo)
│       │   ├── ConstraintActivity.kt
│       │   ├── LinearActivity.kt
│       │   ├── RelativeActivity.kt
│       │   └── TableActivity.kt
│       └── res/
│           ├── layout/
│           │   ├── activity_login.xml
│           │   ├── activity_main.xml (Comparativo)
│           │   ├── activity_constraint.xml
│           │   ├── activity_linear_demo.xml
│           │   ├── activity_relative.xml
│           │   └── activity_table.xml
│           └── values/
│               ├── strings.xml
│               ├── colors.xml
│               └── themes.xml
```

---

## ⚙️ Pré-requisitos e Como Executar

1. **Pré-requisitos:**
   - Android Studio (versão Hedgehog ou superior recomendada).
   - JDK 17 ou superior.
   - Android SDK (API 24 ou superior).

2. **Passos para executar:**
   - Clone o repositório:
     ```bash
     git clone https://github.com/herobruno/Layouts-Android.git
     ```
   - Abra o projeto no **Android Studio**.
   - Sincronize o projeto com o Gradle (`Sync Project with Gradle Files`).
   - Execute o aplicativo em um emulador ou dispositivo físico Android.

---

## 📄 Licença

Este projeto foi desenvolvido para fins acadêmicos e educacionais de desenvolvimento mobile Android.
