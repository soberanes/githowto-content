---
view: page
title: "3. Creando un Proyecto"
---

<h3>Objetivos</h3>

<ul><li>Aprender a crear un repositorio git desde cero.</li></ul>

<h2><em>01</em> Crear una p&aacute;gina "Hello, World"</h2>

<p>Comienza con un directorio de trabajo vac&iacute;o (por ejemplo, Work, si descargaste el archivo del paso anterior), despu&eacute;s crea el archivo <code>hello.html</code> en &eacute;l con el siguiente contenido.</p>

<h4 class="h4-pre">Ejecuta:</h4>

<pre class="instructions">mkdir hello
cd hello
touch hello.html</pre>

<h4 class="h4-pre">Archivo: <em>hello.html</em></h4>

<pre class="file">Hello, World</pre>

<h2><em>02</em> Crear un repositorio</h2>

<p>Ya tienes un directorio que contiene un archivo. Ejecuta git init para crear un repositorio git en ese directorio.</p>

<h4 class="h4-pre">Ejecuta:</h4>

<pre class="instructions">git init</pre>

<h4 class="h4-pre">Resultado:</h4>

<pre class="sample">$ git init
Initialized empty Git repository in /Users/alex/Documents/Presentations/githowto/auto/hello/.git/
</pre>

<h2><em>03</em> Agregar la p&aacute;gina al repositorio</h2>

<p>Ahora agreguemos la p&aacute;gina “Hello, World” al repositorio.</p>

<h4 class="h4-pre">Ejecuta:</h4>

<pre class="instructions">git add hello.html
git commit -m "First Commit"</pre>

<p>Ver&aacute;s &#8230;</p>

<h4 class="h4-pre">Resultado:</h4>

<pre class="sample">$ git add hello.html
$ git commit -m "First Commit"
[master (root-commit) 911e8c9] First Commit
 1 files changed, 1 insertions(+), 0 deletions(-)
 create mode 100644 hello.html</pre>
