## 🇬🇧 English README

# Vibe - Daily Mood Tracker 🌈

Vibe is a simple, elegant web application designed to help users track their daily mood and emotional well-being. By logging how you feel each day along with accompanying notes, you can gain insights into your emotional patterns over time. The application stores data locally in your browser using `localStorage`.

## ✨ Features

* **Mood Selection:** Easily select your current mood from five options:
    * 😄 Very Happy
    * 😊 Happy
    * 😐 Neutral
    * 😔 Sad
    * 😢 Very Sad
* **Date Entry:** Specify the date for each mood entry. Defaults to the current day.
* **Daily Notes:** Add detailed notes about your day, what happened, and how you feel.
* **Save Entries:** Store your mood, date, and notes. The save button is enabled only when a mood, date, and note are provided.
* **Update Entries:** If you create a new entry for a date that already has one, the existing entry will be updated.
* **Visual Feedback:** Get immediate visual confirmation when an entry is saved.
* **Mood History:** View a chronological list of all your past mood entries, with the most recent appearing first.
* **Local Storage:** All data is saved directly in your web browser's `localStorage`, ensuring privacy and offline access.
* **Responsive Design:** The interface adapts to different screen sizes, making it usable on desktops and mobile devices.
* **Chart Placeholders:**
    * **Mood Distribution (Pie Chart):** HTML and Chart.js setup for a pie chart to visualize the overall distribution of your moods.
    * **Mood Frequency (Bar Chart):** HTML and Chart.js setup for a bar chart to show the frequency of each mood.
    * *(Note: The JavaScript logic for populating these charts is not yet implemented in the provided `VibeApp` class, but the infrastructure is present.)*

## 🛠️ Technologies Used

* **HTML5:** For the basic structure of the application.
* **CSS3:** For styling, including flexbox, grid, gradients, and responsive design.
* **JavaScript (ES6+):** For the application logic, DOM manipulation, and event handling.
* **Chart.js (v3.9.1):** A JavaScript library for creating charts (imported via CDN).
* **localStorage API:** For client-side storage of mood data.

## 🚀 Getting Started

1.  **Download:**
    * Save the provided HTML code as an `.html` file (e.g., `vibe.html` or `index.html`).
2.  **Open in Browser:**
    * Open the HTML file directly in any modern web browser (like Chrome, Firefox, Edge, Safari).
    * No web server or complex setup is needed.

## 💻 How to Use

1.  **Select Your Mood:** Click on one of the emoji mood options (e.g., "😄 Very Happy") that best represents how you are feeling.
2.  **Choose the Date:** The current date is selected by default. You can change it using the date picker if you're logging for a past day.
3.  **Write Your Notes:** In the "📝 Daily Notes" text area, write about your day, any significant events, or your reflections. (Original: "📝 Anotações do dia")
4.  **Save Your Entry:** Once a mood is selected, a date is chosen, and notes are written, the "💾 Save Entry" button will become active. Click it to save your entry. (Original: "💾 Salvar Registro")
    * You'll see a "✅ Saved!" confirmation on the button. (Original: "✅ Salvo!")
5.  **View History:** Scroll down to the "📅 Mood History" section to see all your saved entries, with the newest ones at the top. (Original: "📅 Histórico de Humor")
6.  **View Charts (Future):** The "📊 Mood Analysis" section is set up to display a pie chart of mood distribution and a bar chart of mood frequency. Currently, these will appear as empty chart areas as the data binding logic in JavaScript is pending. (Original: "📊 Análise do Humor")

## 📁 File Structure

The entire application (HTML, CSS, and JavaScript) is contained within a single HTML file.

* `<style>` tags: Contain all the CSS rules.
* `<script>` tags: Contain the `VibeApp` JavaScript class and initialization logic.
* `<script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/3.9.1/chart.min.js"></script>`: Imports the Chart.js library from a CDN.

## 🔮 Potential Future Enhancements

* **Implement Chart Rendering:** Add JavaScript logic to populate the Pie and Bar charts using the saved mood data.
* **Data Export/Import:** Allow users to export their mood data (e.g., as JSON or CSV) and import it back.
* **Themes & Customization:** Offer different color themes or layout options.
* **Search/Filter History:** Add functionality to search or filter mood entries by date, mood, or keywords in notes.
* **Mood Trends:** Develop more advanced analytics, like showing mood trends over weeks or months.
* **Password Protection/Cloud Sync (Advanced):** For users who want more privacy or cross-device access (would require a backend).
* **Reminders:** Option to set daily reminders to log mood.

---

## 🇧🇷 README em Português (Brasil)

# Vibe - Registro de Humor Diário 🌈

Vibe é uma aplicação web simples e elegante projetada para ajudar os usuários a registrar seu humor diário e bem-estar emocional. Ao registrar como você se sente a cada dia, juntamente com notas complementares, você pode obter insights sobre seus padrões emocionais ao longo do tempo. A aplicação armazena os dados localmente no seu navegador usando `localStorage`.

## ✨ Funcionalidades

* **Seleção de Humor:** Selecione facilmente seu humor atual entre cinco opções:
    * 😄 Muito Feliz
    * 😊 Feliz
    * 😐 Neutro
    * 😔 Triste
    * 😢 Muito Triste
* **Entrada de Data:** Especifique a data para cada registro de humor. O padrão é o dia atual.
* **Anotações Diárias:** Adicione notas detalhadas sobre o seu dia, o que aconteceu e como você se sente.
* **Salvar Registros:** Armazene seu humor, data e notas. O botão de salvar é habilitado apenas quando um humor, data e anotação são fornecidos.
* **Atualizar Registros:** Se você criar um novo registro para uma data que já possui um, o registro existente será atualizado.
* **Feedback Visual:** Obtenha confirmação visual imediata quando um registro é salvo.
* **Histórico de Humor:** Visualize uma lista cronológica de todos os seus registros de humor anteriores, com os mais recentes aparecendo primeiro.
* **Armazenamento Local (`localStorage`):** Todos os dados são salvos diretamente no `localStorage` do seu navegador, garantindo privacidade e acesso offline.
* **Design Responsivo:** A interface se adapta a diferentes tamanhos de tela, tornando-a utilizável em desktops e dispositivos móveis.
* **Espaço para Gráficos:**
    * **Distribuição de Humor (Gráfico de Pizza):** Configuração HTML e Chart.js para um gráfico de pizza para visualizar a distribuição geral dos seus humores.
    * **Frequência de Humor (Gráfico de Barras):** Configuração HTML e Chart.js para um gráfico de barras para mostrar a frequência de cada humor.
    * *(Observação: A lógica JavaScript para popular esses gráficos ainda não está implementada na classe `VibeApp` fornecida, mas a infraestrutura está presente.)*

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Para a estrutura básica da aplicação.
* **CSS3:** Para estilização, incluindo flexbox, grid, gradientes e design responsivo.
* **JavaScript (ES6+):** Para a lógica da aplicação, manipulação do DOM e tratamento de eventos.
* **Chart.js (v3.9.1):** Uma biblioteca JavaScript para criar gráficos (importada via CDN).
* **API `localStorage`:** Para armazenamento de dados do lado do cliente.

## 🚀 Como Começar

1.  **Baixar:**
    * Salve o código HTML fornecido como um arquivo `.html` (por exemplo, `vibe.html` ou `index.html`).
2.  **Abrir no Navegador:**
    * Abra o arquivo HTML diretamente em qualquer navegador moderno (como Chrome, Firefox, Edge, Safari).
    * Nenhum servidor web ou configuração complexa é necessária.

## 💻 Como Usar

1.  **Selecione Seu Humor:** Clique em uma das opções de humor com emoji (por exemplo, "😄 Muito Feliz") que melhor representa como você está se sentindo.
2.  **Escolha a Data:** A data atual é selecionada por padrão. Você pode alterá-la usando o seletor de data se estiver registrando um dia passado.
3.  **Escreva Suas Anotações:** Na área de texto "📝 Anotações do dia", escreva sobre o seu dia, eventos significativos ou suas reflexões.
4.  **Salve Seu Registro:** Assim que um humor for selecionado, uma data for escolhida e as anotações forem escritas, o botão "💾 Salvar Registro" ficará ativo. Clique nele para salvar seu registro.
    * Você verá uma confirmação "✅ Salvo!" no botão.
5.  **Veja o Histórico:** Role para baixo até a seção "📅 Histórico de Humor" para ver todos os seus registros salvos, com os mais novos no topo.
6.  **Veja os Gráficos (Futuro):** A seção "📊 Análise do Humor" está configurada para exibir um gráfico de pizza da distribuição de humor e um gráfico de barras da frequência de humor. Atualmente, eles aparecerão como áreas de gráfico vazias, pois a lógica de vinculação de dados em JavaScript está pendente.

## 📁 Estrutura de Arquivos

Toda a aplicação (HTML, CSS e JavaScript) está contida em um único arquivo HTML.

* Tags `<style>`: Contêm todas as regras CSS.
* Tags `<script>`: Contêm a classe JavaScript `VibeApp` e a lógica de inicialização.
* `<script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/3.9.1/chart.min.js"></script>`: Importa a biblioteca Chart.js de uma CDN.

## 🔮 Possíveis Melhorias Futuras

* **Implementar Renderização de Gráficos:** Adicionar lógica JavaScript para popular os gráficos de Pizza e Barras usando os dados de humor salvos.
* **Exportar/Importar Dados:** Permitir que os usuários exportem seus dados de humor (por exemplo, como JSON ou CSV) e os importem de volta.
* **Temas e Personalização:** Oferecer diferentes temas de cores ou opções de layout.
* **Pesquisar/Filtrar Histórico:** Adicionar funcionalidade para pesquisar ou filtrar registros de humor por data, humor ou palavras-chave nas anotações.
* **Tendências de Humor:** Desenvolver análises mais avançadas, como mostrar tendências de humor ao longo de semanas ou meses.
* **Proteção por Senha/Sincronização na Nuvem (Avançado):** Para usuários que desejam mais privacidade ou acesso entre dispositivos (exigiria um backend).
* **Lembretes:** Opção para definir lembretes diários para registrar o humor.


![](.\site_01.png)
![](.\site_02.png)