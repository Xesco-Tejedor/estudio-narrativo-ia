# 🎨 Estudio Narrativo IA: La teva Suite Creativa Integral

| Llicència | Estat              | Versió |
|-----------|--------------------|--------|
| MIT       | En Desenvolupament | 0.2.0  |

Benvingut/da a **Estudio Narrativo IA**! La suite de creació literària definitiva, impulsada per la IA de Gemini. Combina gèneres, genera narratives extenses, il·lustra les teves escenes amb una immensa llibreria d'estils artístics i exporta el teu projecte complet. Dissenyat per a escriptors, dissenyadors de jocs, mestres de rol i qualsevol ment creativa que busqui una eina potent i versàtil.

---

### 🚀 Prova'l Ara Online! 🚀

No cal instal·lar res. Pots començar a crear les teves històries a l'instant accedint a la demo online.

**[Accedeix a la Demo Online Fent Clic Aquí](https://estudio-narrativo-ia-298249200473.us-west1.run.app)**

*Exemple: Defineix una història de "Fantasia" + "Ciència Ficció", afegeix els teus elements clau i genera un text i imatges úniques amb estil "Moebius" o "Frank Frazetta".*

---

### ✨ Característiques Principals

*   🧭 **Flux de Treball Modular:** Un procés guiat pas a pas a través de mòduls (Resum, Gènere, Narrativa, Imatges, Exportació) per organitzar la teva creació de manera intuïtiva i ordenada.

*   🔬 **Mescla de Gèneres Híbrids:**
    *   Selecciona i combina fins a 3 gèneres literaris d'una llista predefinida (Fantasia, Ciència Ficció, Misteri, etc.).
    *   Sistema de pesos percentuals (`%`) totalment ajustable per controlar amb precisió la influència de cada gènere en la teva història.
    *   Visualització en temps real de la distribució per a una barreja equilibrada.

*   ✍️ **Generació de Narrativa Intel·ligent:**
    *   Crea històries complexes basades en un títol i "elements clau" que tu defineixes.
    *   Controla la longitud aproximada i tria entre diversos estils narratius (Descriptiu, Poètic, Terror, etc.).
    *   Capacitat única per **continuar una narrativa existent**, afegint nous fragments de manera coherent per crear obres extenses.

*   🖼️ **Generador d'Imatges Il·lustratives:**
    *   Genera il·lustracions espectaculars basades en les teves descripcions (`prompts`).
    *   Accés a una **extensa llibreria de més de 50 estils artístics**, curosament organitzats per categories: Mestres Històrics, Fantasia i Ciència Ficció, Còmic, Animació, etc.
    *   Inclou estils de mestres llegendaris com *Frazetta, Moebius, Mignola, Ghibli, Van Gogh, Rembrandt* i molts més.
    *   Selecciona entre múltiples relacions d'aspecte (Quadrat, Paisatge, Retrat) per a la composició perfecta.

*   🎨 **Gestor d'Estils Artístics Personalitzable:**
    *   No estàs limitat als estils predefinits! Afegeix, edita i gestiona la teva pròpia col·lecció.
    *   **Afegeix els teus propis estils artístics** personalitzats amb nom, `prompt` tècnic, categoria i color identificatiu.
    *   **Edita i elimina** els estils que has creat per adaptar la llibreria exactament a les teves necessitats creatives.

*   💾 **Exportació Versàtil de Projectes:**
    *   Descarrega la teva obra completa en múltiples formats professionals.
    *   **HTML**: Un fitxer autocontingut i interactiu amb la teva història i una galeria d'imatges amb lightbox. Perfecte per compartir o imprimir a PDF.
    *   **Markdown**: Ideal per a editors de text, blogs o sistemes de gestió de continguts.
    *   **Text Pla (.txt)**: Només la narrativa, sense cap format, per a màxima compatibilitat.
    *   **JSON**: Exporta tota l'estructura del projecte, incloent metadades, imatges i text, per a preservació o importació futura.

---

### 🔧 Configuració Local

1.  **Clonar el Repositori:**
    ```bash
    git clone https://github.com/google-gemini-vignettes/estudio-narrativo-ia.git
    cd estudio-narrativo-ia
    ```
2.  **Requisit de la Clau API:**
    Aquesta aplicació requereix una clau API de Google Gemini per funcionar. El codi està configurat per llegir aquesta clau de la variable d'entorn `process.env.API_KEY`. Abans d'executar l'aplicació, has d'assegurar-te que aquesta variable estigui configurada i accessible en el teu entorn d'execució.

3.  **Execució:**
    Un cop la variable d'entorn estigui configurada, serveix els arxius a través d'un servidor web local i obre l'aplicació al teu navegador.

---

### 🎯 Com Utilitzar l'Estudi

1.  **Inicia el Projecte:** A la barra lateral, dona un **Títol** al teu projecte i descriu els **Elements Clau** de la teva història. Aquests elements són la llavor de la teva creació.
2.  **Defineix el Gènere:** Ves al mòdul **Gènere**. Selecciona fins a 3 gèneres i ajusta els seus pesos fins que la barreja sumi 100%.
3.  **Crea la Narrativa:** Al mòdul **Narrativa IA**, tria l'estil i la longitud desitjada i fes clic a "Generar". Pots prémer el botó de nou per **continuar** la història des d'on l'has deixat.
4.  **Il·lustra la teva Història:** Ves a **Imatges IA**. Escriu un `prompt` per a una escena, tria un estil artístic de l'extensa llista (o un de teu!), ajusta els paràmetres i genera la imatge. Repeteix per a totes les il·lustracions que necessitis.
5.  **Exporta la teva Obra:** Finalment, al mòdul **Exportar**, tria el teu format preferit (HTML recomanat per a una presentació completa) i descarrega el teu projecte acabat.

---

### 🗺️ Full de Ruta i Millores Futures

*   🌗 **Mode Fosc** per a una millor experiència visual en sessions de creació nocturnes.
*   💾 **Guardar/Carregar Projectes** a l'emmagatzematge local del navegador per no perdre el teu progrés.
*   🌐 **Traducció de la Interfície** a altres idiomes (castellà, anglès).
*   📄 **Més opcions d'exportació** com PDF directe i ePub.
*   👥 **Gestor de Personatges i Línies Temporals** com a nous mòduls per a una organització més profunda.

---

### 🚀 Tecnologies Utilitzades

*   **React 19** & **TypeScript** per a una interfície moderna i robusta.
*   **Tailwind CSS** per a un disseny ràpid, personalitzable i responsiu.
*   **Google Gemini API** (`@google/genai`) per a la generació de text i imatges d'última generació.
*   **ESM via esm.sh**: Configuració moderna que funciona directament al navegador sense necessitat d'un paquetitzador (`no-bundle`).
*   **React-based**: Estructura totalment modular i componentitzada per a una millor mantenibilitat.

---

### 📄 Llicència

Aquest projecte està sota la **Llicència MIT**.

*Forjant mons, una paraula i un píxel a la vegada. 🎨✍️*

---

### 🙌 Com Contribuir

Les contribucions són més que benvingudes! Si tens idees per millorar l'Estudi Narrativo IA, has trobat un error o vols afegir una nova funcionalitat:

1.  Fes un `Fork` del projecte.
2.  Crea una *feature branch* (`git checkout -b feature/AmazingFeature`).
3.  Fes `Commit` dels teus canvis (`git commit -m 'Add some AmazingFeature'`).
4.  Fes `Push` a la branch (`git push origin feature/AmazingFeature`).
5.  Obre una `Pull Request`.

---
### 📞 Contacte i Suport

Tens preguntes, suggeriments o necessites ajuda? La millor manera és a través de GitHub:

*   🐛 **Reportar Bugs:** Obre un *issue* a la secció d'Issues del repositori.
*   💡 **Suggerir Característiques:** Inicia una discussió a la secció de Discussions.

*Creat amb algoritmes creatius, IA generativa i molta imaginació.*
