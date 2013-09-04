<div id="table-of-contents">
<h2>Table of Contents</h2>
<div id="text-table-of-contents">
<ul>
<li><a href="#sec-1">1. Goal</a></li>
<li><a href="#sec-2">2. installation and use</a>
<ul>
<li><a href="#sec-2-1">2.1. installation</a></li>
<li><a href="#sec-2-2">2.2. use</a></li>
</ul>
</li>
<li><a href="#sec-3">3. Tasks</a>
<ul>
<li><a href="#sec-3-1">3.1. </a></li>
</ul>
</li>
</ul>
</div>
</div>


# Goal

To have a **very simple** presentation tool inside emacs, navigating
through the *org topics*.

It is completely based on **org-presie** (thanks to [Nic Ferrier](nferrier@ferrier.me.uk) who
first created the org-presie)

# installation and use

## installation

-   copy the file `org-presie.el` into your *el* directory

-   insert into `init.el` the command:
    
    `(require 'org-presie)`
    
    ps: if you have the above file in any other directory, first
    insert this line to your `init.el`:
    
    `(add-to-list 'load-path "~/<directory you have org-presie.el
        file>")`

## use

In any *org file*, press **<f5>** and it will change to PRES-minor
mode

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col class="left"/>

<col class="left"/>
</colgroup>
<tbody>
<tr>
<td class="left">Key</td>
<td class="left">command</td>
</tr>


<tr>
<td class="left"><f5></td>
<td class="left">toggle PRES minor mode inside an ORG buffer</td>
</tr>


<tr>
<td class="left">right (arrow)</td>
<td class="left">Advance 5 lines or until next topic (any level) - what comes first</td>
</tr>


<tr>
<td class="left">left (arrow)</td>
<td class="left">back one line at a time</td>
</tr>


<tr>
<td class="left">esc-right</td>
<td class="left">Advance to next topic</td>
</tr>


<tr>
<td class="left">esc-left</td>
<td class="left">back to previous topic</td>
</tr>
</tbody>
</table>

# Tasks

## TODO 
