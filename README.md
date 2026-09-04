# Layouts-Android 📱

Aplicativo Android desenvolvido em Kotlin para demonstrar e comparar os principais sistemas de gerenciamento de layout em Android (XML Views).

---

## 🚀 Sobre o Projeto

Este projeto tem como objetivo servir de guia e referência prática para o uso de diferentes layouts no desenvolvimento Android nativo. Ele apresenta exemplos funcionais e estruturados para cada um dos principais grupos de layout disponíveis no SDK do Android.

---

## 🛠️ Layouts Demonstrados

O aplicativo demonstra o funcionamento dos seguintes layouts:

1. **ConstraintLayout (`activity_constraint.xml`)**
   - O layout mais flexível e recomendado para interfaces complexas. Permite posicionar e dimensionar widgets em relação a outros elementos e ao container pai usando restrições (*constraints*).

2. **LinearLayout (`activity_linear_demo.xml`)**
   - Organiza os elementos filhos em uma única direção: linearmente na vertical (`vertical`) ou na horizontal (`horizontal`). Ideal para listas simples e formulários lineares.

3. **RelativeLayout (`activity_relative.xml`)**
   - Permite posicionar elementos filhos em posições relativas uns aos outros (ex: à esquerda de, abaixo de) ou em relação ao container pai.

4. **TableLayout (`activity_table.xml`)**
   - Organiza os elementos em linhas (`TableRow`) e colunas, ideal para dados tabulares ou grades estruturadas.

---

## 📂 Estrutura do Projeto

```text
app/
├── src/
│   └── main/
│       ├── java/com/example/login/
│       │   ├── MainActivity.kt
│       │   ├── ConstraintActivity.kt
│       │   ├── LinearActivity.kt
│       │   ├── RelativeActivity.kt
│       │   └── TableActivity.kt
│       └── res/
│           ├── layout/
│           │   ├── activity_main.xml
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

## 👨‍💻 Autor

Desenvolvido por **Bruno Souza** ([@herobruno](https://github.com/herobruno)).
