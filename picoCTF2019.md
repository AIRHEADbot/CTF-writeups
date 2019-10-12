---


---

<h1 id="picoctf2019-writeup"><em>picoCTF2019-writeup</em></h1>
<h2 id="warm"><em>2Warm</em></h2>
<h3 id="chanllenge"><em>Chanllenge</em></h3>
<p>Can you convert the number 42 (base 10) to binary (base 2)?</p>
<h3 id="solution"><em>Solution</em></h3>
<p>单纯的进制转换</p>
<h3 id="flag"><em>Flag</em></h3>
<blockquote>
<p>picoCTF{101010}</p>
</blockquote>
<h2 id="glory-of-the-garden"><em>Glory of the Garden</em></h2>
<h3 id="chanllenge-1"><em>Chanllenge</em></h3>
<p>This <a href="https://2019shell1.picoctf.com/static/6b58b3859f377f1cf4cabb0188d35e5c/garden.jpg">garden</a> contains more than it seems. You can also find the file in /problems/glory-of-the-garden_5_eeb712a9a3bc1998ffcd626af9d63f98 on the shell server.</p>
<h3 id="solution-1"><em>Solution</em></h3>
<p>Winhex查看文件16进制码，flag在ANSI ASCII末尾</p>
<h3 id="flag-1"><em>Flag</em></h3>
<blockquote>
<p>picoCTF{more_than_m33ts_the_3y3cD8bA96C}</p>
</blockquote>
<h2 id="insp3ct0r"><em>Insp3ct0r</em></h2>
<h3 id="chanllenge-2"><em>Chanllenge</em></h3>
<p>Kishor Balan tipped us off that the following code may need inspection: <code>https://2019shell1.picoctf.com/problem/52962/</code> (<a href="https://2019shell1.picoctf.com/problem/52962/">link</a>) or <a href="http://2019shell1.picoctf.com:52962">http://2019shell1.picoctf.com:52962</a></p>
<h3 id="solution-2"><em>Solution</em></h3>
<p>检查网页源码，发现以下三段信息<br>
index:</p>
<blockquote>
<p>!-- Html is neat. Anyways have 1/3 of the flag: picoCTF{tru3_d3 –</p>
</blockquote>
<p>mycss.css:</p>
<blockquote>
<p>You need CSS to make pretty pages. Here’s part 2/3 of the flag: t3ct1ve_0r_ju5t</p>
</blockquote>
<p>myjs.js:</p>
<blockquote>
<p>Javascript sure is neat. Anyways part 3/3 of the flag: _lucky?39dd9e36}</p>
</blockquote>
<h3 id="flag-2"><em>Flag</em></h3>
<blockquote>
<p>picoCTF{tru3_d3t3ct1ve_0r_ju5t_lucky?39dd9e36}</p>
</blockquote>
<h2 id="lets-warm-up"><em>Lets Warm Up</em></h2>
<h3 id="chanllenge-3"><em>Chanllenge</em></h3>
<p>If I told you a word started with 0x70 in hexadecimal, what would it start with in ASCII?</p>
<h3 id="solution-3"><em>Solution</em></h3>
<p>16进制转ASCii码</p>
<h3 id="flag-3"><em>Flag</em></h3>
<blockquote>
<p>picoCTF{p}</p>
</blockquote>

