---
view: page
title: "1. Preparaci&oacute;n"
---

<h3>Objetivos</h3>

<ul><li>Estar preparado totalmente para trabajar con Git.</li></ul>

<h2><em>01</em> Configurar nombre y correo electr&oacute;nico</h2>

<p>Si nunca has usado Git anteriormente, primero necesitas configurar tu nombre y tu correo electr&oacute;nico. Ejecuta los siguientes comandos para que git conozca tu nombre y tu correo electr&oacute;nico. Si git ya est&aacute; instalado, avanza hasta el final de la l&iacute;nea.</p>

<h4 class="h4-pre">Ejecuta:</h4>

<pre class="instructions">git config --global user.name "Your Name"
git config --global user.email "your_email@whatever.com"</pre>

<h2><em>02</em> Opciones de instalación finales de línea</h2>

<p>También, para usuarios de Unix/Mac:</p>

<h4 class="h4-pre">Ejecuta:</h4>

<pre class="instructions">git config --global core.autocrlf input
git config --global core.safecrlf true</pre>

<p>Para usuarios de Windows:</p>

<h4 class="h4-pre">Ejecuta:</h4>

<pre class="instructions">git config --global core.autocrlf true
git config --global core.safecrlf true</pre>
