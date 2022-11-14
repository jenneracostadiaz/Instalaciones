# Configuraciones adicionales para VSCode

Primero tenemos que abrir nuestro <code>JSON</code> de Configuraciones para nuestro VSCode, lo abrimos usando el siguiente atajo de teclado: <code>Ctrl + Shift + P</code> y buscamos: <code>settings.json</code>

## Configuración del Theme synthwave84
Establecemos el brillo en <code>settings.json</code>:
<pre>
{
    "synthwave84.brightness": 0.45
}
</pre>
Debido a que habilitar el brillo modifica los archivos principales, el código VS interpretará esto como que el núcleo está 'corrompido' y es posible que vea un mensaje de error al reiniciar su editor. Puede descartar este mensaje de forma segura o eliminarlo por completo con la extensión [Fix VSCode Checksums](https://marketplace.visualstudio.com/items?itemName=lehni.vscode-fix-checksums) .

Tras la instalación de 'Fix VSCode Checksums', abra la paleta de comandos y ejecute Fix Checksums: Apply. Deberá reiniciar completamente VSCode después de la ejecución; volver a abrir sin salir por completo podría no ser suficiente.

## 