# 🎨 Estudio Narrativo IA: La teva Suite Creativa Integral

Llicència | Estat | Versió
--- | --- | ---
MIT | En Desenvolupament | 0.1.0

Benvingut/da a **Estudio Narrativo IA**! La suite de creació literària definitiva, impulsada per la IA de Gemini. Combina gèneres, genera narratives extenses, il·lustra les teves escenes amb una immensa llibreria d'estils artístics i exporta el teu projecte complet. Dissenyat per a escriptors, dissenyadors de jocs, mestres de rol i qualsevol ment creativa que busqui una eina potent i versàtil.

---

### ✨ Característiques Principals

*   🧭 **Flux de Treball Modular:** Un procés guiat pas a pas a través de mòduls (Resum, Gènere, Narrativa, Imatges, Exportació) per organitzar la teva creació.
*   🔬 **Mescla de Gèneres Híbrids:**
    *   Selecciona i combina fins a 3 gèneres literaris d'una llista predefinida.
    *   Sistema de pesos ajustables (`%`) per controlar la influència de cada gènere en la història.
    *   Valida que la suma total sigui 100% per a una barreja equilibrada.
*   ✍️ **Generació de Narrativa Intel·ligent:**
    *   Crea històries basades en un títol i "elements clau" que defineixes.
    *   Defineix la longitud aproximada i l'estil (Narratiu, Poètic, Terror, etc.).
    *   Capacitat per **continuar una narrativa existent**, afegint nous fragments de manera coherent.
*   🖼️ **Generador d'Imatges Il·lustratives:**
    *   Genera imatges basades en les teves descripcions (`prompts`).
    *   Accés a una **extensa llibreria de més de 50 estils artístics**, organitzats per categories (Mestres Històrics, Fantasia, Còmic, Animació, etc.).
    *   Inclou estils de mestres com *Frazetta, Moebius, Mignola, Ghibli, Van Gogh* i molts més.
    *   Selecciona diferents relacions d'aspecte (1:1, 16:9, 9:16...).
*   🎨 **Gestor d'Estils Artístics Personalitzable:**
    *   No estàs limitat als estils predefinits!
    *   **Afegeix els teus propis estils artístics** personalitzats amb nom, `prompt` i categoria.
    *   **Edita i elimina** els estils que has creat per adaptar la llibreria a les teves necessitats.
*   💾 **Exportació Versàtil de Projectes:**
    *   Descarrega la teva obra completa en múltiples formats.
    *   **HTML**: Un fitxer autocontingut i interactiu amb la teva història i una galeria d'imatges amb lightbox. Perfecte per compartir o imprimir.
    *   **Markdown**: Ideal per a editors de text o sistemes de gestió de continguts.
    *   **Text Pla (.txt)**: Només la narrativa, sense format.
    *   **JSON**: Exporta tota l'estructura del projecte, incloent metadades, per a preservació o importació futura.

---

### 🔧 Configuració Local

Aquesta aplicació funciona directament al navegador però requereix una clau API de Google per comunicar-se amb els models de Gemini. Per executar-la localment, el més senzill és utilitzar un servidor de desenvolupament que pugui gestionar variables d'entorn.

1.  **Clonar el Repositori:**
    ```bash
    git clone https://github.com/el-teu-usuari/estudio-narrativo-ia.git
    cd estudio-narrativo-ia
    ```
2.  **Configurar la Clau API:**
    El projecte espera una variable d'entorn (`process.env.API_KEY`). Si utilitzes un entorn com **Vite**, pots fer el següent:
    *   Crea un fitxer anomenat `.env.local` a l'arrel del projecte.
    *   Afegeix la teva clau API dins d'aquest fitxer:
        ```
        VITE_API_KEY=LA_TEVA_CLAU_API_DE_GEMINI
        ```
    *   **Important**: Perquè funcioni amb Vite, hauràs de modificar `services/geminiService.ts` per llegir `import.meta.env.VITE_API_KEY` en lloc de `process.env.API_KEY`.
3.  **Executar el Servidor de Desenvolupament:**
    Si no tens un entorn de Node.js configurat, simplement pots obrir `index.html` en un navegador, però hauràs de substituir manualment `process.env.API_KEY` a `services/geminiService.ts` amb la teva clau per a proves.

---

### 🎯 Com Utilitzar l'Estudi

1.  **Inicia el Projecte:** A la barra lateral, dona un **Títol** al teu projecte i descriu els **Elements Clau** de la teva història.
2.  **Defineix el Gènere:** Ves al mòdul **Gènere**. Selecciona fins a 3 gèneres i ajusta els seus pesos fins a sumar 100%.
3.  **Crea la Narrativa:** Al mòdul **Narrativa IA**, tria l'estil i la longitud i fes clic a "Generar". Pots continuar generant més text sobre el resultat.
4.  **Il·lustra la teva Història:** Ves a **Imatges IA**. Escriu un `prompt` per a una escena, tria un estil artístic de la llista (o un de personalitzat) i genera la imatge. Repeteix per a totes les il·lustracions que necessitis.
5.  **Exporta la teva Obra:** Finalment, al mòdul **Exportar**, tria el teu format preferit i descarrega el projecte complet.

---

### 🗺️ Full de Ruta

*   **Mode Fosc** per a una millor experiència visual.
*   **Guardar/Carregar Projectes** a l'emmagatzematge local del navegador.
*   **Traducció de la Interfície** a altres idiomes (castellà, anglès).
*   **Més opcions d'exportació** (PDF, ePub).
*   **Gestor de Personatges i Línies Temporals** com a nous mòduls.

---

### 🚀 Tecnologies Utilitzades

*   **React 19** & **TypeScript**
*   **Tailwind CSS** per a un disseny ràpid i responsiu.
*   **Google Gemini API** (`@google/genai`) per a la generació de text i imatges.
*   **ESM via esm.sh**: Configuració moderna sense paquetitzador (`no-bundle`).
*   **React-based**: Estructura modular i componentitzada.

---

### 📄 Llicència

Aquest projecte està sota la **Llicència MIT**.

Forjant mons, una paraula i un píxel a la vegada. 🎨✍️
