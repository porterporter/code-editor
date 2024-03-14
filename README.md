# Code Editor

This simple example that allows for code input with syntax highlighting and error checking.
> To try out the example, run `>Live Preview: Start Server` in the VSCode command pallet.

## Dependencies

Here are the main dependencies used in this project:

### Monaco Editor

Monaco Editor is a browser-based code editor that features rich IntelliSense, validation for TypeScript, JavaScript, CSS, LESS, SCSS, JSON, HTML, and more. It's developed by Microsoft and is open source.

### Constrained Editor Plugin

Constrained Editor Plugin is a plugin for the Monaco Editor that allows you to restrict the user's ability to edit certain parts of the code.

## Installation

You can add these dependencies to your project by including the following tags in your `index.html` file:

```html
<!-- Monaco Editor CSS -->
<link rel="stylesheet" data-name="vs/editor/editor.main" href="https://www.unpkg.com/monaco-editor/min/vs/editor/editor.main.css">

<!-- Monaco Editor JS -->
<script src="https://cdn.jsdelivr.net/npm/monaco-editor/min/vs/loader.js"></script>

<!-- Constrained Editor Plugin -->
<script src="https://cdn.jsdelivr.net/npm/constrained-editor-plugin@1.3.0/dist/constrainedEditorPlugin.min.js"></script>
```