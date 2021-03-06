---
view: page
title: "7. Индексация и коммит"
---

<p>Отдельный шаг индексации в git позволяет вам продолжать вносить изменения в рабочий каталог, а затем, в момент, когда вы захотите взаимодействовать с версионным контролем, git позволит записать изменения в малых коммитах, которые фиксируют то, что вы сделали.</p>

<p>Предположим, что вы отредактировали три файла (<code>a.html</code>, <code>b.html</code>, and <code>c.html</code>). Теперь вы хотите закоммитить все изменения, при этом чтобы изменения в <code>a.html</code> и <code>b.html</code> были одним коммитом, в то время как изменения в <code>c.html</code> логически не связаны с первыми двумя файлами и должны идти отдельным коммитом.</p>

<p>В теории, вы можете сделать следующее:</p>

<pre class="instructions">git add a.html
git add b.html
git commit -m "Changes for a and b"</pre>

<pre class="instructions">git add c.html
git commit -m "Unrelated change to c"</pre>

<p>Разделяя индексацию и коммит, вы имеете возможность с легкостью настроить, что идет в какой коммит.</p>