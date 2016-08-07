
<h2>Porter Stemming Algorithm</h2>
Porter stemming is a process of removing the common morphological and inflexional endings of words. <br><br>
It can be thought of as a lexicon finite state transducer with the following steps: <br>
<ul>
  <li>Surface form -> </li> 
  <li>split word into possible morphemes -> </li>
  <li>getting intermediate form -> </li>
  <li>map stems to categories and affixes to meaning -> </li>
  <li>underlying form. </li>
</ul>
I.e : foxes -> fox + s -> fox.

<h3> How to execute ? </h3>

<code> 
python StemWord.py
</code>
<br>
<i> YOUR INPUT</i><br>
<i> YOUR OUTPUT</i><br>
<br>

For example:<br>
<code>python StemWord.py</code><br>
FOXES<br>
FOX<br>
</p>
