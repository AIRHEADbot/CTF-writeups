---


---

<h1 id="picoctf2019-writeup"><em>picoCTF2019-writeup</em></h1>
<h2 id="general-skills"><em>General Skills</em></h2>
<h2 id="warm"><em>2Warm</em></h2>
<h4 id="chanllenge"><em>Chanllenge</em></h4>
<p>Can you convert the number 42 (base 10) to binary (base 2)?</p>
<h4 id="solution"><em>Solution</em></h4>
<p>单纯的进制转换</p>
<h4 id="flag"><em>Flag</em></h4>
<blockquote>
<p>picoCTF{101010}</p>
</blockquote>
<h2 id="lets-warm-up"><em>Lets Warm Up</em></h2>
<h4 id="chanllenge-1"><em>Chanllenge</em></h4>
<p>If I told you a word started with 0x70 in hexadecimal, what would it start with in ASCII?</p>
<h4 id="solution-1"><em>Solution</em></h4>
<p>16进制转ASCii码</p>
<h4 id="flag-1"><em>Flag</em></h4>
<blockquote>
<p>picoCTF{p}</p>
</blockquote>
<h2 id="warmed-up"><em>Warmed Up</em></h2>
<h4 id="chanllenge-2"><em>Chanllenge</em></h4>
<p>What is 0x3D (base 16) in decimal (base 10).</p>
<h4 id="solution-2"><em>Solution</em></h4>
<p>又是进制转换</p>
<h4 id="flag-2"><em>Flag</em></h4>
<blockquote>
<p>picoCTF{61}</p>
</blockquote>
<h2 id="bases"><em>Bases</em></h2>
<h4 id="chanllenge-3"><em>Chanllenge</em></h4>
<p>What does this <code>bDNhcm5fdGgzX3IwcDM1</code> mean? I think it has something to do with bases</p>
<h4 id="solution-3"><em>Solution</em></h4>
<p>Base64</p>
<h4 id="flag-3"><em>Flag</em></h4>
<blockquote>
<p>picoCTF{l3arn_th3_r0p35}</p>
</blockquote>
<h2 id="first-grep"><em>First Grep</em></h2>
<h4 id="chanllenge-4"><em>Chanllenge</em></h4>
<p>Can you find the flag in <a href="https://2019shell1.picoctf.com/static/20314c5941bbf36a5eaa2e0926fb1cb5/file">file</a>? This would be really tedious to look through manually, something tells me there is a better way. You can also find the file in /problems/first-grep_3_2e09f586a51352180a37e25913f5e5d9 on the shell server.</p>
<h4 id="solution-4"><em>Solution</em></h4>
<p>考察grep基础用法</p>
<blockquote>
<p>$ grep pico file</p>
</blockquote>
<p>或</p>
<blockquote>
<p>$ ./file | grep pico*</p>
</blockquote>
<h4 id="flag-4"><em>Flag</em></h4>
<blockquote>
<p>picoCTF{grep_is_good_to_find_things_eda8911c}</p>
</blockquote>
<h2 id="resources"><em>Resources</em></h2>
<h4 id="chanllenge-5"><em>Chanllenge</em></h4>
<p>We put together a bunch of resources to help you out on our website! If you go over there, you might even find a flag! <code>https://picoctf.com/resources</code> (<a href="https://picoctf.com/resources">link</a>)</p>
<h4 id="solution-5"><em>Solution</em></h4>
<p>打开链接就知道了</p>
<h4 id="flag-5"><em>Flag</em></h4>
<blockquote>
<p><code>picoCTF{r3source_pag3_f1ag}</code></p>
</blockquote>
<h2 id="strings-it"><em>strings it</em></h2>
<h4 id="chanllenge-6"><em>Chanllenge</em></h4>
<p>Can you find the flag in <a href="https://2019shell1.picoctf.com/static/762b9a36a6da791e3f61713fcfaf1721/strings">file</a> without running it? You can also find the file in /problems/strings-it_2_865eec66d190ef75386fb14e15972126 on the shell server.</p>
<h4 id="solution-6"><em>Solution</em></h4>
<p>在终端使用以下指令：</p>
<blockquote>
<p>$ ls<br>
$ strings ./strings | grep pico</p>
</blockquote>
<h4 id="flag-6"><em>Flag</em></h4>
<blockquote>
<p>picoCTF{5tRIng5_1T_d5b86184}</p>
</blockquote>
<h2 id="whats-a-net-cat"><em>what’s a net cat</em></h2>
<h4 id="chanllenge-7"><em>Chanllenge</em></h4>
<p>Using netcat (nc) is going to be pretty important. Can you connect to <code>2019shell1.picoctf.com</code> at port <code>47229</code> to get the flag?</p>
<h4 id="solution-7"><em>Solution</em></h4>
<p>考察nc的基本用法：<br>
nc + 网址 + 端口</p>
<blockquote>
<p>$ nc <a href="http://2019shell1.picoctf.com">2019shell1.picoctf.com</a> 4158</p>
</blockquote>
<h4 id="flag-7"><em>Flag</em></h4>
<blockquote>
<p>picoCTF{nEtCat_Mast3ry_700da9c7}</p>
</blockquote>
<h2 id="based"><em>Based</em></h2>
<h4 id="chanllenge-8"><em>Chanllenge</em></h4>
<p>To get truly 1337, you must understand different data encodings, such as hexadecimal or binary. Can you get the flag from this program to prove you are on the way to becoming 1337? Connect with <code>nc 2019shell1.picoctf.com 7380</code>.</p>
<h4 id="solution-8"><em>Solution</em></h4>
<p>netcat连接至题目<br>
依次为二进制、八进制、十六进制转码</p>
<h4 id="flag-8"><em>Flag</em></h4>
<blockquote>
<p>picoCTF{learning_about_converting_values_819ada06}</p>
</blockquote>
<h2 id="first-grep-part-ii"><em>First Grep: Part II</em></h2>
<h4 id="chanllenge-9"><em>Chanllenge</em></h4>
<p>Can you find the flag in /problems/first-grep–part-ii_2_1c866f894e7ef69b77a69a224b0c3f60/files on the shell server? Remember to use grep.</p>
<h4 id="solution-9"><em>Solution</em></h4>
<p>连接至终端</p>
<blockquote>
<p>$ grep -r “pico”</p>
</blockquote>
<p>或</p>
<blockquote>
<p>$ find . -name “file*” -type f | xargs grep picoCTF</p>
</blockquote>
<h4 id="flag-9"><em>Flag</em></h4>
<blockquote>
<p>picoCTF{grep_r_to_find_this_ee829ae6}</p>
</blockquote>
<h2 id="plumbing"><em>plumbing</em></h2>
<h4 id="chanllenge-10"><em>Chanllenge</em></h4>
<p>Sometimes you need to handle process data outside of a file. Can you find a way to keep the output from this program and search for the flag? Connect to <code>2019shell1.picoctf.com 63345</code>.</p>
<h4 id="solution-10"><em>Solution</em></h4>
<p>netcat连接后发现显示了太多无用字符</p>
<blockquote>
<p>nc <a href="http://2019shell1.picoctf.com">2019shell1.picoctf.com</a> 63345  | grep pico</p>
</blockquote>
<h4 id="flag-10"><em>Flag</em></h4>
<blockquote>
<p>picoCTF{digital_plumb3r_4e7a5813}</p>
</blockquote>
<h2 id="whats-the-difference"><em>whats-the-difference</em></h2>
<h4 id="chanllenge-11"><em>Chanllenge</em></h4>
<p>Can you spot the difference? <a href="https://2019shell1.picoctf.com/static/473cf765877f28edf95140f90cd76b59/kitters.jpg">kitters</a>  <a href="https://2019shell1.picoctf.com/static/473cf765877f28edf95140f90cd76b59/cattos.jpg">cattos</a>. They are also available at /problems/whats-the-difference_0_00862749a2aeb45993f36cc9cf98a47a on the shell server</p>
<h4 id="solution-11"><em>Solution</em></h4>
<p>本题给出两张图片<br>
根据提示使用winhex找不同<br>
将不同的字符找到即为flag<br>
或者在Linux终端：</p>
<blockquote>
<p>$ hexdump -C kitters.jpg&gt; kitters.txt<br>
$ hexdump -C cattos.jpg&gt; cattos.txt<br>
$ colordiff kitters.txt cattos.txt | grep -v“ ---”</p>
</blockquote>
<h4 id="flag-11"><em>Flag</em></h4>
<blockquote>
<p>picoCTF{th3yr3_a5_d1ff3r3nt_4s_bu773r_4nd_j311y_aslkjfdsalkfslkflkjdsfdszmz10548}</p>
</blockquote>
<h2 id="where-is-the-file"><em>where-is-the-file</em></h2>
<h4 id="chanllenge-12"><em>Chanllenge</em></h4>
<p>I’ve used a super secret mind trick to hide this file. Maybe something lies in /problems/where-is-the-file_3_19c1a7766ac2747c446eb9666a9b4fb4.</p>
<h4 id="solution-12"><em>Solution</em></h4>
<p>打开文件夹显示隐藏文件夹</p>
<blockquote>
<p>$ ls -a</p>
</blockquote>
<p>发现一个叫做 <code>.cant_see_me</code> 的文件夹<br>
用cat看看有什么</p>
<blockquote>
<p>$ cat .cant_see_me</p>
</blockquote>
<h4 id="flag-12"><em>Flag</em></h4>
<blockquote>
<p>picoCTF{w3ll_that_d1dnt_w0RK_f28cde66}</p>
</blockquote>
<h2 id="flag_shop"><em>flag_shop</em></h2>
<h4 id="chanllenge-13"><em>Chanllenge</em></h4>
<p>There’s a flag shop selling stuff, can you buy a flag? <a href="https://2019shell1.picoctf.com/static/66f01ee2332244dd8290bbefb604a74b/store.c">Source</a>. Connect with <code>nc 2019shell1.picoctf.com 3967</code>.</p>
<h4 id="solution-13"><em>Solution</em></h4>
<p>发现购买flag要很多钱，但是你却没办法氪金，怎么办？<br>
阅读源码，考虑在购买使出现整数溢出的情况。<br>
<img src="https://lh3.googleusercontent.com/zXVHjNSza_Xgp9x9F8zyecJSA5gZm0XydPXx-JTWqWhO8QC4v3qrLM-xlL_a6FKWz-PqYsDeirc" alt="enter image description here" title="flag_shop"><br>
然后就可以购买正确flag啦！</p>
<h4 id="flag-13"><em>Flag</em></h4>
<blockquote>
<p>picoCTF{m0n3y_bag5_cd0ead78}</p>
</blockquote>
<h2 id="mus1c"><em>mus1c</em></h2>
<h4 id="chanllenge-14"><em>Chanllenge</em></h4>
<p>I wrote you a <a href="https://2019shell1.picoctf.com/static/24287456e17d7ee3a35147517fcb9305/lyrics.txt">song</a>. Put it in the picoCTF{} flag format</p>
<h4 id="solution-14"><em>Solution</em></h4>
<p>请不要忽视Hints！<br>
Rockstar是一种语言编译器！<br>
<a href="https://github.com/marcinruszkiewicz/kaiser-ruby">https://github.com/marcinruszkiewicz/kaiser-ruby</a><br>
按照README里的提示进行安装，再使用KaiserRuby工具执行吧。<br>
个人认为这题考察最关键的是信息收集能力orz</p>
<h4 id="flag-14"><em>Flag</em></h4>
<blockquote>
<p>picoCTF{rrrocknrn0113r}</p>
</blockquote>
<h2 id="wanna_b3_a_r0ck5tar"><em>1_wanna_b3_a_r0ck5tar</em></h2>
<h4 id="chanllenge-15"><em>Chanllenge</em></h4>
<p>I wrote you another <a href="https://2019shell1.picoctf.com/static/8ee87fa624458921e43b786696e37f7f/lyrics.txt">song</a>. Put the flag in the picoCTF{} flag format</p>
<h4 id="solution-15"><em>Solution</em></h4>
<p>???</p>
<h4 id="flag-15"><em>Flag</em></h4>
<blockquote>
<p>???</p>
</blockquote>
<h2 id="forensics"><em>Forensics</em></h2>
<h2 id="glory-of-the-garden"><em>Glory of the Garden</em></h2>
<h4 id="chanllenge-16"><em>Chanllenge</em></h4>
<p>This <a href="https://2019shell1.picoctf.com/static/6b58b3859f377f1cf4cabb0188d35e5c/garden.jpg">garden</a> contains more than it seems. You can also find the file in /problems/glory-of-the-garden_5_eeb712a9a3bc1998ffcd626af9d63f98 on the shell server.</p>
<h4 id="solution-16"><em>Solution</em></h4>
<p>Winhex查看文件16进制码，flag在ANSI ASCII末尾</p>
<h4 id="flag-16"><em>Flag</em></h4>
<blockquote>
<p>picoCTF{more_than_m33ts_the_3y3cD8bA96C}</p>
</blockquote>
<h2 id="unzip"><em>unzip</em></h2>
<h4 id="chanllenge-17"><em>Chanllenge</em></h4>
<p>Can you unzip this <a href="https://2019shell1.picoctf.com/static/37762a7e5774d7d6c1bc79e8e1758ef9/flag.zip">file</a> and get the flag?</p>
<h4 id="solution-17"><em>Solution</em></h4>
<p>解压文件，白给</p>
<h4 id="flag-17"><em>Flag</em></h4>
<blockquote>
<p>picoCTF{unz1pp1ng_1s_3a5y}</p>
</blockquote>
<h2 id="so-meta"><em>So Meta</em></h2>
<h4 id="chanllenge-18"><em>Chanllenge</em></h4>
<p>Find the flag in this <a href="https://2019shell1.picoctf.com/static/051b66965016a24bb62e5af66b28cbc0/pico_img.png">picture</a>. You can also find the file in /problems/so-meta_2_da856426d694a4f0637bf1b169d8524e.</p>
<h4 id="solution-18"><em>Solution</em></h4>
<p>在终端上用strings提取字符串<br>
或者下载图片使用winhex查看，flag在最后</p>
<h4 id="flag-18"><em>Flag</em></h4>
<blockquote>
<p>picoCTF{s0_m3ta_3d6ced35}</p>
</blockquote>
<h2 id="what-lies-within"><em>What Lies Within</em></h2>
<h4 id="chanllenge-19"><em>Chanllenge</em></h4>
<p>Theres something in the <a href="https://2019shell1.picoctf.com/static/aec3861fc4d5bce4d39dc0db196426de/buildings.png">building</a>. Can you retrieve the flag?</p>
<h4 id="solution-19"><em>Solution</em></h4>
<p>查看每个通道的LSB值可得<br>
<img src="https://lh3.googleusercontent.com/hJdw8WwHhM3VdbPV7-VuMdxRIUGn6BEj4rfq5-l-2CNewlcpVdp8Spof_WOelNBALtuulqyKF3o" alt="enter image description here" title="buildings"></p>
<h4 id="flag-19"><em>Flag</em></h4>
<blockquote>
<p>picoCTF{h1d1ng_1n_th3_b1t5}</p>
</blockquote>
<h2 id="extensions"><em>extensions</em></h2>
<h4 id="chanllenge-20"><em>Chanllenge</em></h4>
<p>This is a really weird text file <a href="https://2019shell1.picoctf.com/static/45886ed4b6d5d1dc74c4944fcf4b4041/flag.txt">TXT</a>? Can you find the flag?</p>
<h4 id="solution-20"><em>Solution</em></h4>
<p>拓展名改为png即可</p>
<h4 id="flag-20"><em>Flag</em></h4>
<blockquote>
<p>picoCTF{now_you_know_about_extensions}</p>
</blockquote>
<h2 id="shark-on-wire-1"><em>shark on wire 1</em></h2>
<h4 id="chanllenge-21"><em>Chanllenge</em></h4>
<p>We found this  <a href="https://2019shell1.picoctf.com/static/ae9ca8cff43ed638ed5d137f9ece7455/capture.pcap">packet capture</a>. Recover the flag. You can also find the file in /problems/shark-on-wire-1_0_13d709ec13952807e477ba1b5404e620.</p>
<p>Submit!</p>
<h4 id="solution-21"><em>Solution</em></h4>
<h4 id="flag-21"><em>Flag</em></h4>
<blockquote>
<p>？？？</p>
</blockquote>
<h2 id="whitepages"><em>WhitePages</em></h2>
<h4 id="chanllenge-22"><em>Chanllenge</em></h4>
<p>I stopped using YellowPages and moved onto WhitePages… but <a href="https://2019shell1.picoctf.com/static/e134178261c6fa36e9058d5408118dd9/whitepages.txt">the page they gave me</a> is all blank!</p>
<h4 id="solution-22"><em>Solution</em></h4>
<p>用Geany和Winhex查看后，发现文件中的空白有两种模式（\xe2\x80\83 &amp; \x20)<br>
ps:\x20是ASCII的空格表示，而\xe2\x80\83是Unicode的空格表示<br>
既然有两种模式，猜想可转化为MorseCode<br>
将<code>e28083</code>视作<code>0</code> 或<code></code>，<code>20</code>视作<code>1</code> 或<code>_</code></p>
<h4 id="flag-22"><em>Flag</em></h4>
<blockquote>
<p>picoCTF{not_all_spaces_are_created_equal_dd5c2e2f77f89f3051c82bfee7d996ef}</p>
</blockquote>
<h2 id="c0rrupt"><em>c0rrupt</em></h2>
<h4 id="chanllenge-23"><em>Chanllenge</em></h4>
<p>We found this <a href="https://2019shell1.picoctf.com/static/3435d990f1d20fe3563cbb897b4c96db/mystery">file</a>. Recover the flag. You can also find the file in /problems/c0rrupt_0_1fcad1344c25a122a00721e4af86de13.</p>
<h4 id="solution-23"><em>Solution</em></h4>
<p>这是一道修复png文件头的题目<br>
修复结果如下：<br>
<img src="https://lh3.googleusercontent.com/dLAzfwrNtTwtjNdt3GDVrL7UvNNE6QuCKrynPMSMucQn6IiiqA-lMA43Os14jKvF9LuZlVjT4AE" alt="enter image description here" title="c0rrupt"><br>
此处有几个关键点：PNG文件署名、CRC（校验值）、IDAT（图像数据块）标识。而中间的gAMA、PHYs等都是关键数据块中的可选项。</p>
<h4 id="flag-23"><em>Flag</em></h4>
<blockquote>
<p>picoCTF{c0rrupt10n_1847995}</p>
</blockquote>
<h2 id="like1000"><em>like1000</em></h2>
<h4 id="chanllenge-24"><em>Chanllenge</em></h4>
<p>This <a href="https://2019shell1.picoctf.com/static/8694f84879d3b7c0dcf775930f4665fc/1000.tar">.tar file</a> got tarred alot. Also available at /problems/like1000_0_369bbdba2af17750ddf10cc415672f1c.</p>
<h4 id="solution-24"><em>Solution</em></h4>
<p>这是个压缩了1000次的压缩包，半小时之内肯定能手动解压出来的（确信）当然，我更推荐编写脚本进行解压。</p>
<blockquote>
<p>from os import system</p>
<p>system(‘unar ./1000.tar’)<br>
for i in range(999, -1, -1):<br>
system(‘unar ./{}/{}.tar’.format(i+1, i))</p>
</blockquote>
<h4 id="flag-24"><em>Flag</em></h4>
<blockquote>
<p>picoCTF{l0t5_0f_TAR5}</p>
</blockquote>
<h2 id="m00nwalk"><em>m00nwalk</em></h2>
<h4 id="chanllenge-25"><em>Chanllenge</em></h4>
<p>Decode this  <a href="https://2019shell1.picoctf.com/static/f5ca745ad5d88a890b5f20b8ffde3d70/message.wav">message</a>  from the moon. You can also find the file in /problems/m00nwalk_4_bcf65d52e5462dd0b70c0e984d7d5015.</p>
<h4 id="solution-25"><em>Solution</em></h4>
<p>Hints告诉我们，这可能和地月消息传输有关。经过查阅资料，我们发现有关传输方法为SSTV（Slow-scan television）。这是一种图片传输方法。</p>
<h4 id="flag-25"><em>Flag</em></h4>
<blockquote></blockquote>
<h2 id="cryptography"><em>Cryptography</em></h2>
<h2 id="the-numbers"><em>The Numbers</em></h2>
<h4 id="chanllenge-26"><em>Chanllenge</em></h4>
<p>The <a href="https://2019shell1.picoctf.com/static/eb3589c566dd3f809908053460acb817/the_numbers.png">numbers</a>… what do they mean?</p>
<h4 id="solution-26"><em>Solution</em></h4>
<p><img src="https://2019shell1.picoctf.com/static/eb3589c566dd3f809908053460acb817/the_numbers.png" alt="enter image description here"><br>
显然是26个字母和数字一一对应</p>
<h4 id="flag-26"><em>Flag</em></h4>
<blockquote>
<p>PICOCTF{THENUMBERSMASON}</p>
</blockquote>
<h2 id="section"><em>13</em></h2>
<h4 id="chanllenge-27"><em>Chanllenge</em></h4>
<p>Cryptography can be easy, do you know what ROT13 is? <code>cvpbPGS{abg_gbb_onq_bs_n_ceboyrz}</code></p>
<h4 id="solution-27"><em>Solution</em></h4>
<p>最基础的Caesar cipher<br>
也称ROT13<br>
最简易的替换式密码<br>
<a href="https://rot13.com/">https://rot13.com/</a></p>
<h4 id="flag-27"><em>Flag</em></h4>
<blockquote>
<p>picoCTF{not_too_bad_of_a_problem}</p>
</blockquote>
<h2 id="easy1"><em>Easy1</em></h2>
<h4 id="chanllenge-28"><em>Chanllenge</em></h4>
<p>The one time pad can be cryptographically secure, but not when you know the key. Can you solve this? We’ve given you the encrypted flag, key, and a table to help <code>UFJKXQZQUNB</code> with the key of <code>SOLVECRYPTO</code>. Can you use this <a href="https://2019shell1.picoctf.com/static/30d4405c34cf6490b082e6cf8f56ac56/table.txt">table</a> to solve it?.</p>
<h4 id="solution-28"><em>Solution</em></h4>
<p>杰弗逊盘</p>
<h4 id="flag-28"><em>Flag</em></h4>
<blockquote>
<p>picoCTF{CRYPTOISFUN}</p>
</blockquote>
<h2 id="caesar"><em>caesar</em></h2>
<h4 id="chanllenge-29"><em>Chanllenge</em></h4>
<p>Decrypt this <a href="https://2019shell1.picoctf.com/static/b67dd108828e8d030d7babaeb89df172/ciphertext">message</a>. You can find the ciphertext in /problems/caesar_2_10e2c1660e7b34790d93f61a1e4dd9d9 on the shell server.</p>
<h4 id="solution-29"><em>Solution</em></h4>
<p>Caesar cipher</p>
<h4 id="flag-29"><em>Flag</em></h4>
<blockquote>
<p>picoCTF{crossingtherubiconvrtezsxl}</p>
</blockquote>
<h2 id="web"><em>Web</em></h2>
<h2 id="insp3ct0r"><em>Insp3ct0r</em></h2>
<h4 id="chanllenge-30"><em>Chanllenge</em></h4>
<p>Kishor Balan tipped us off that the following code may need inspection: <code>https://2019shell1.picoctf.com/problem/52962/</code> (<a href="https://2019shell1.picoctf.com/problem/52962/">link</a>) or <a href="http://2019shell1.picoctf.com:52962">http://2019shell1.picoctf.com:52962</a></p>
<h3 id="solution-30"><em>Solution</em></h3>
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
<h3 id="flag-30"><em>Flag</em></h3>
<blockquote>
<p>picoCTF{tru3_d3t3ct1ve_0r_ju5t_lucky?39dd9e36}</p>
</blockquote>
<h2 id="dont-use-client-side"><em>dont-use-client-side</em></h2>
<h4 id="chanllenge-31"><em>Chanllenge</em></h4>
<p>Can you break into this super secure portal? <code>https://2019shell1.picoctf.com/problem/37893/</code> (<a href="https://2019shell1.picoctf.com/problem/37893/">link</a>) or <a href="http://2019shell1.picoctf.com:37893">http://2019shell1.picoctf.com:37893</a></p>
<h4 id="solution-31"><em>Solution</em></h4>
<p>检查网页源码</p>
<blockquote>
<p>function verify() {<br>
checkpass = document.getElementById(“pass”).value;<br>
split = 4;<br>
if (checkpass.substring(0, split) == ‘pico’) {<br>
if (checkpass.substring(split<em>6, split</em>7) == ‘0ff3’) {<br>
if (checkpass.substring(split, split<em>2) == ‘CTF{’) {<br>
if (checkpass.substring(split</em>4, split<em>5) == ‘ts_p’) {<br>
if (checkpass.substring(split</em>3, split<em>4) == ‘lien’) {<br>
if (checkpass.substring(split</em>5, split<em>6) == ‘lz_9’) {<br>
if (checkpass.substring(split</em>2, split<em>3) == ‘no_c’) {<br>
if (checkpass.substring(split</em>7, split*8) == ‘4}’) {<br>
alert(“Password Verified”)<br>
…</p>
</blockquote>
<p>根据顺序还原flag</p>
<h4 id="flag-31"><em>Flag</em></h4>
<blockquote>
<p>picoCTF{no_clients_plz_90ff34}</p>
</blockquote>
<h2 id="logon"><em>logon</em></h2>
<h4 id="chanllenge-32"><em>Chanllenge</em></h4>
<p>The factory is hiding things from all of its users. Can you login as logon and find what they’ve been looking at? <code>https://2019shell1.picoctf.com/problem/49907/</code> (<a href="https://2019shell1.picoctf.com/problem/49907/">link</a>) or <a href="http://2019shell1.picoctf.com:49907">http://2019shell1.picoctf.com:49907</a></p>
<h4 id="solution-32"><em>Solution</em></h4>
<p>经过尝试，发现非admin用户可以登录，却无法获得flag。查看网页cookie，将其中admin元素False改为True。</p>
<h3 id="flag-32"><em>Flag</em></h3>
<blockquote>
<p>picoCTF{th3_c0nsp1r4cy_l1v3s_9e21365b}</p>
</blockquote>
<h2 id="strings-it-1"><em>strings it</em></h2>
<h4 id="chanllenge-33"><em>Chanllenge</em></h4>
<p>Can you find the flag in <a href="https://2019shell1.picoctf.com/static/762b9a36a6da791e3f61713fcfaf1721/strings">file</a> without running it? You can also find the file in /problems/strings-it_2_865eec66d190ef75386fb14e15972126 on the shell server.</p>
<h4 id="solution-33"><em>Solution</em></h4>
<h4 id="flag-33"><em>Flag</em></h4>
<blockquote></blockquote>
<h2 id="section-1">**</h2>
<h4 id="chanllenge-34"><em>Chanllenge</em></h4>
<h4 id="solution-34"><em>Solution</em></h4>
<h4 id="flag-34"><em>Flag</em></h4>
<blockquote></blockquote>

