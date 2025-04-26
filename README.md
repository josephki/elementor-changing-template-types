# elementor-changing-template-types
Changing the template types in elementor not implemented - a little code snippet

# Anleitung: Elementor Template Type Changer

## Übersicht

Der Elementor Template Type Changer ermöglicht es dir, den Typ eines bestehenden Elementor-Templates nachträglich zu ändern - eine Funktion, die Elementor standardmäßig nicht anbietet. Mit diesem Tool kannst du beispielsweise ein Template vom Typ "Seite" in einen "Abschnitt" oder "Container" umwandeln.

## Installation

1. Kopiere den Code des Plugins in die `functions.php` deines Themes oder Child-Themes
2. Alternativ: Verwende ein Code-Snippet-Plugin wie "Code Snippets" und füge den Code dort ein
3. Nach der Installation findest du unter "Tools" einen neuen Menüpunkt "Elementor Type Changer"

## Verwendung

### Schritt 1: Template exportieren
1. Gehe zu "Elementor" > "Templates" im WordPress-Admin
2. Finde das Template, dessen Typ du ändern möchtest
3. Klicke auf das Drei-Punkte-Menü und wähle "Exportieren"
4. Die JSON-Datei wird auf deinen Computer heruntergeladen

### Schritt 2: Template-Typ ändern
1. Gehe zu "Tools" > "Elementor Type Changer" im WordPress-Admin
2. Klicke auf "Datei auswählen" und wähle die exportierte JSON-Datei
3. Wähle den gewünschten neuen Template-Typ aus der Dropdown-Liste
4. Klicke auf "Template-Typ ändern"
5. Klicke auf "Geänderte Datei herunterladen", um die modifizierte JSON-Datei zu speichern

### Schritt 3: Geändertes Template importieren
1. Gehe zurück zu "Elementor" > "Templates"
2. Klicke auf den Button "Import Templates"
3. Wähle die modifizierte JSON-Datei aus
4. Klicke auf "Import jetzt"
5. Nach dem Import erscheint das Template in der gewählten Kategorie

## Hinweise

- Das Original-Template bleibt unverändert erhalten. Das Tool erstellt ein neues Template mit dem geänderten Typ.
- Nach dem Import kannst du das Original-Template löschen, falls nicht mehr benötigt.
- Diese Methode funktioniert mit allen Elementor-Templates, einschließlich denen von JetPlugins.
- Unterstützte Template-Typen: Seite, Abschnitt, Container, Widget, Globales Widget, Floating Element, Kopfzeile, Fußzeile, Single, Single Post, Single Page, Archiv, Suchergebnisse, 404, Loop Item, Popup und viele weitere.

## Fehlerbehebung

- Falls der Import fehlschlägt, prüfe, ob die JSON-Datei korrekt heruntergeladen wurde.
- Stelle sicher, dass deine Elementor-Version aktuell ist.
- Bei Problemen mit speziellen Template-Typen (wie Jet-Plugin-Templates), stelle sicher, dass das entsprechende Plugin installiert und aktiviert ist.

------------------------- Englisch -------------------------
# Guide: Elementor Template Type Changer

## Overview

The Elementor Template Type Changer allows you to change the type of an existing Elementor template - a feature that Elementor doesn't offer by default. With this tool, you can convert a template from "Page" type to "Section", "Container", or any other template type.

## Installation

1. Copy the plugin code into your theme's `functions.php` file or child theme
2. Alternatively: Use a code snippet plugin like "Code Snippets" and add the code there
3. After installation, you'll find a new menu item "Elementor Type Changer" under "Tools"

## Usage

### Step 1: Export Template
1. Go to "Elementor" > "Templates" in your WordPress admin
2. Find the template whose type you want to change
3. Click on the three-dots menu and select "Export"
4. The JSON file will be downloaded to your computer

### Step 2: Change Template Type
1. Go to "Tools" > "Elementor Type Changer" in your WordPress admin
2. Click "Choose File" and select the exported JSON file
3. Select the desired new template type from the dropdown list
4. Click "Change Template Type"
5. Click "Download Modified File" to save the modified JSON file

### Step 3: Import Modified Template
1. Go back to "Elementor" > "Templates"
2. Click the "Import Templates" button
3. Select the modified JSON file
4. Click "Import Now"
5. After import, the template appears in the chosen category

## Notes

- The original template remains unchanged. The tool creates a new template with the changed type.
- After importing, you can delete the original template if no longer needed.
- This method works with all Elementor templates, including those from JetPlugins.
- Supported template types: Page, Section, Container, Widget, Global Widget, Floating Element, Header, Footer, Single, Single Post, Single Page, Archive, Search Results, 404, Loop Item, Popup, and many more.

## Troubleshooting

- If the import fails, check if the JSON file was downloaded correctly.
- Make sure your Elementor version is up to date.
- If you have issues with special template types (like Jet plugin templates), ensure the corresponding plugin is installed and activated.
