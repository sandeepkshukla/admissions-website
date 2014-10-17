---
title: Home
atom: /atom.xml
---

Welcome to the admissions page.

### Announcements

$for(announcements)$
<div class="row">

<div class="col-sm-2">
$partial("templates/date-panel.html")$
</div>

<div class="col-sm-10">

### $title$

$if(teaser)$
$teaser$

<a class="btn btn-default pull-right" href="$url$">Read more</a>

$else$
$body$

<a class="btn btn-default pull-right" href="$url$">Permalink</a>
$endif$
</div>

</div>
<hr/>
$endfor$
* [More...](/announcements.html)