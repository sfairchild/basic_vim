# Basic Commands

--

## Move single character

<h1><pre><code style="text-align: center;">
k
h   l
j
</code></pre></h1>


--

## Move by word and WORD

This&nbsp;"stuff" is not-so difficult!<!-- .element: style="font-family: 'Courier New', Courier, monospace;" -->

wwww&nbsp;&nbsp;wwwww&nbsp;&nbsp;ww www ww wwwwwwwww&nbsp;<!-- .element: style="font-family: 'Courier New', Courier, monospace;" -->

WWWW WWWWWWW WW WWWWWW WWWWWWWWWW<!-- .element: style="font-family: 'Courier New', Courier, monospace;" -->


<h2><pre><code style="text-align: center;">
By word
b ge w e
</code></pre></h2>


<h2><pre><code style="text-align: center;">
By WORD
B gE W E
</code></pre></h2>

--

## Find and Till

<dl>
  <dt>f{char}</dt>
  <dd>find the first character that matches {char}</dd>
  <dt>t{char}</dt>
  <dd>find the character before first the character that matches {char}</dd>
  <dt>F{char}</dt>
  <dd>find the first character that matches {char} backwards</dd>
  <dt>T{char}</dt>
  <dd>find the character after first the character that matches {char} backwards</dd>
</dl>

--

## Search for word

<dl>
  <dt>/{text}</dt>
  <dl>find text in file after cursor</dl>
  <dt>?{text}</dt>
  <dl>find text in file before cursor</dl>
  <dt>\*</dt>
  <dl>find word under cursor</dl>
  <dt>#</dt>
  <dl>find word under cursor before current location</dl>
  <dt>n</dt>
  <dl>continue search in same direction</dl>
  <dt>N</dt>
  <dl>continue search in opposite direction</dl>
</dl>

--

## Navigate the buffer

<dl>
  <dt>gg</dt>
  <dd>goto the top of the buffer</dd>
  <dt>{line number}G</dt>
  <dd>goto the line number</dd>
  <dt>G</dt>
  <dd>goto the end of file</dd>
</dl>

