---




# Getting Started with deck.js #

---

## How to Make a Deck ##

### Write Slides ###

Slide content is simple HTML

### Choose Themes ###

One for slide styles and one for deck transitions

### Include Extensions ###

Add extra functionality to your deck or leave it stripped down.

--- 

<img src = 'http://placehold.it/700x500' class = 'vcenter'/>

---

<style>
pre.knitr {
  font-family: 'Consolas';
  font-size: 18px;
}
</style>

## Some Code ##


<div class="chunk"><div class="rcode"><div class="source"><pre class="knitr R"><span class="functioncall">citet</span><span class="keyword">(</span><span class="functioncall">c</span><span class="keyword">(</span><span class="argument">Halpern2006</span> <span class="argument">=</span> <span class="string">"10.1111/j.1461-0248.2005.00827.x"</span><span class="keyword">)</span><span class="keyword">)</span>
<span class="comment"># then cite in your markdown file</span>
<span class="functioncall">citet</span><span class="keyword">(</span><span class="string">"Halpern2006"</span><span class="keyword">)</span>


<span class="comment"># or read citations from a bibtex file which can be automatically generated and updated from services like Mendeley</span>

<span class="symbol">bib</span> <span class="assignement">&lt;-</span> <span class="functioncall">read.bibtex</span><span class="keyword">(</span><span class="string">"example.bib"</span><span class="keyword">)</span>
<span class="comment"># then cite inline</span>
<span class="functioncall">citet</span><span class="keyword">(</span><span class="symbol">bib</span><span class="keyword">[[</span><span class="string">"knitr"</span><span class="keyword">]</span><span class="keyword">]</span><span class="keyword">)</span>
</pre></div></div></div>


---

<iframe class = 'vcenter' width="853" height="480" src="http://www.youtube.com/embed/Me5Ss7PZGP0?rel=0" frameborder="0" allowfullscreen></iframe>

---

<div class="chunk"><div class="rimage vcenter"><img src="figure/graph.png" class="plot" /></div></div>


---

## Wolfram Demo

<script type='text/javascript' src='http://demonstrations.wolfram.com/javascript/embed.js' ></script><script type='text/javascript'>var demoObj = new DEMOEMBED(); demoObj.run('MicrowaveOven', '', '489', '625');</script><div id='DEMO_MicrowaveOven'><a class='demonstrationHyperlink' href='http://demonstrations.wolfram.com/MicrowaveOven/' target='_blank'>Microwave Oven</a> from the <a class='demonstrationHyperlink' href='http://demonstrations.wolfram.com/' target='_blank'>Wolfram Demonstrations Project</a> by S. M. Blinder</div>
