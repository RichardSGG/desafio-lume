# 🚀 Desafio Técnico LUME 2026

## Flutter — Meu Cartão Digital

Seja bem-vindo(a) ao **Desafio Técnico LUME 2026**! 🎉  
Este projeto tem como objetivo avaliar e consolidar os conhecimentos básicos de **Layout e Widgets no Flutter**, por meio da construção de uma **interface estática** que simula um **cartão de visitas digital profissional**.

---

## 🛠️ Requisitos de Ambiente

Antes de iniciar o desafio, certifique-se de que o seu ambiente de desenvolvimento está corretamente configurado:

- ✅ **Flutter SDK** instalado e configurado  
  - Verifique com o comando:
    ```bash
    flutter doctor
    ```
- 🖥️ **Editor de Código**
  - VS Code ou Android Studio
- 📱 **Ambiente de Execução**
  - Emulador, dispositivo físico ou navegador (Flutter Web)

---

## 💡 Recomendações Importantes

Para facilitar o desenvolvimento e evitar problemas de configuração, recomendamos:

* 🔹 **Instalar o Android Studio**, mesmo que não seja utilizado como editor principal.
    > O Android Studio é responsável por configurar corretamente o SDK do Android, emuladores e demais dependências.
* 🔹 **Desenvolver utilizando o VS Code** com a **extensão oficial do Flutter**.
    * Extensões recomendadas: **Flutter** e **Dart**.
* 🔹 **Dependendo da capacidade da sua máquina**, evite instalar emuladores.
    * **Alternativas recomendadas:**
        * 📱 Utilizar um **dispositivo físico**.
        * 🌐 Executar o projeto via **Flutter Web**:
            ```bash
            flutter run -d chrome
            ```

Essas opções reduzem o consumo de recursos e tornam o ambiente de desenvolvimento mais leve.

---

## 🏗️ O Desafio

O projeto deve ser criado **do zero**.

### 📌 Criação do Projeto

Utilize o comando abaixo para criar o projeto:

```bash
flutter create nome_do_seu_projeto
```

- ou usar a extensão do flutter no visual studio code

### 🎨 Requisitos da Interface

A aplicação deve conter os seguintes elementos:

* 👤 **Avatar**
    * Imagem circular utilizando o widget `CircleAvatar`.
* 🧾 **Identificação**
    * `Text` com o seu nome (Fonte maior, estilo negrito).
    * `Text` com o seu cargo.
* 📞 **Informações de Contato**
    * Pelo menos 2 linhas de contato (Ex.: e-mail, LinkedIn, GitHub).
    * Cada linha deve conter um `Icon` e um `Text`, alinhados horizontalmente usando o widget `Row`.
* 📐 **Layout**
    * Conteúdo centralizado na tela.
    * Uso de `SizedBox` ou `Padding` para garantir o espaçamento correto entre os elementos.



---

### 🚩 Regras de Entrega (Obrigatório)

#### 1️⃣ Commits Convencionais
O histórico de commits deve seguir o padrão **Conventional Commits**. Exemplos:
* `feat: add profile avatar and name`
* `style: adjust padding and alignment of contact row`
* `docs: update readme with project info`

#### 2️⃣ Uso de Inteligência Artificial
O uso de IA é permitido, porém **obrigatório documentar**. Caso utilize ferramentas como ChatGPT, Copilot, Gemini, entre outras, crie um arquivo na raiz do projeto chamado:
📄 **`IA_REPORT.md`**

Este arquivo deve conter:
* Os prompts (instruções) enviados à IA.
* Em quais partes do código a IA contribuiu mais.

#### 3️⃣ Prazo e Plataforma
* 📦 O projeto deve estar hospedado em um **repositório público no GitHub**.
* ⏰ **Data limite:** Sábado, 10/01/2026, até às 23:00.

---



### 🍀 Considerações Finais

- não vamos fazer avaliações rigidas, apenas entender o nivel da nossa equipe para designar tarefas baseadas no nivel do desenvolvedor e recomendar estudos.

Desejamos sucesso no **Desafio Técnico LUME 2026**! 🚀

Em caso de dúvidas, consulte a documentação oficial do Flutter em:  
👉 [https://flutter.dev](https://flutter.dev)
