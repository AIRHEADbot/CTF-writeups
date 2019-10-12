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
<h2 id="the-numbers"><em>The Numbers</em></h2>
<h3 id="chanllenge-4"><em>Chanllenge</em></h3>
<p>The <a href="https://2019shell1.picoctf.com/static/eb3589c566dd3f809908053460acb817/the_numbers.png">numbers</a>… what do they mean?</p>
<h3 id="solution-4"><em>Solution</em></h3>
<p><img src="https://2019shell1.picoctf.com/static/eb3589c566dd3f809908053460acb817/the_numbers.png" alt="enter image description here"><br>
显然是26个字母和数字一一对应</p>
<h3 id="flag-4"><em>Flag</em></h3>
<blockquote>
<p>PICOCTF{THENUMBERSMASON}</p>
</blockquote>
<h2 id="warmed-up"><em>Warmed Up</em></h2>
<h3 id="chanllenge-5"><em>Chanllenge</em></h3>
<p>What is 0x3D (base 16) in decimal (base 10).</p>
<h3 id="solution-5"><em>Solution</em></h3>
<p>又是进制转换</p>
<h3 id="flag-5"><em>Flag</em></h3>
<blockquote>
<p>picoCTF{61}</p>
</blockquote>
<h2 id="unzip"><em>unzip</em></h2>
<h3 id="chanllenge-6"><em>Chanllenge</em></h3>
<p>Can you unzip this <a href="https://2019shell1.picoctf.com/static/37762a7e5774d7d6c1bc79e8e1758ef9/flag.zip">file</a> and get the flag?</p>
<h3 id="solution-6"><em>Solution</em></h3>
<p>解压文件，白给</p>
<h3 id="flag-6"><em>Flag</em></h3>
<blockquote>
<p>picoCTF{unz1pp1ng_1s_3a5y}</p>
</blockquote>
<h2 id="section"><em>13</em></h2>
<h3 id="chanllenge-7"><em>Chanllenge</em></h3>
<p>Cryptography can be easy, do you know what ROT13 is? <code>cvpbPGS{abg_gbb_onq_bs_n_ceboyrz}</code></p>
<h3 id="solution-7"><em>Solution</em></h3>
<p>最基础的Caesar cipher<br>
也称ROT13<br>
最简易的替换式密码<br>
<a href="https://rot13.com/">https://rot13.com/</a></p>
<h3 id="flag-7"><em>Flag</em></h3>
<blockquote>
<p>picoCTF{not_too_bad_of_a_problem}</p>
</blockquote>
<h2 id="bases"><em>Bases</em></h2>
<h3 id="chanllenge-8"><em>Chanllenge</em></h3>
<p>What does this <code>bDNhcm5fdGgzX3IwcDM1</code> mean? I think it has something to do with bases</p>
<h3 id="solution-8"><em>Solution</em></h3>
<p>Base64</p>
<h3 id="flag-8"><em>Flag</em></h3>
<blockquote>
<p>picoCTF{l3arn_th3_r0p35}</p>
</blockquote>
<h2 id="easy1"><em>Easy1</em></h2>
<h3 id="chanllenge-9"><em>Chanllenge</em></h3>
<p>The one time pad can be cryptographically secure, but not when you know the key. Can you solve this? We’ve given you the encrypted flag, key, and a table to help <code>UFJKXQZQUNB</code> with the key of <code>SOLVECRYPTO</code>. Can you use this <a href="https://2019shell1.picoctf.com/static/30d4405c34cf6490b082e6cf8f56ac56/table.txt">table</a> to solve it?.</p>
<h3 id="solution-9"><em>Solution</em></h3>
<p>杰弗逊盘</p>
<h3 id="flag-9"><em>Flag</em></h3>
<blockquote>
<p>picoCTF{CRYPTOISFUN}</p>
</blockquote>
<h2 id="first-grep"><em>First Grep</em></h2>
<h3 id="chanllenge-10"><em>Chanllenge</em></h3>
<p>Can you find the flag in <a href="https://2019shell1.picoctf.com/static/20314c5941bbf36a5eaa2e0926fb1cb5/file">file</a>? This would be really tedious to look through manually, something tells me there is a better way. You can also find the file in /problems/first-grep_3_2e09f586a51352180a37e25913f5e5d9 on the shell server.</p>
<h3 id="solution-10"><em>Solution</em></h3>
<p>考察grep基础用法</p>
<blockquote></blockquote>
<h3 id="flag-10"><em>Flag</em></h3>
<blockquote></blockquote>
<h2 id="section-1">**</h2>
<h3 id="chanllenge-11"><em>Chanllenge</em></h3>
<h3 id="solution-11"><em>Solution</em></h3>
<h3 id="flag-11"><em>Flag</em></h3>
<blockquote></blockquote>

