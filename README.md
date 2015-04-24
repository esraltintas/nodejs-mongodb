#Node.js Kurulum

**Linux**


1. Node.js in **.tar.gaz.** uzantılı son versiyonunu [buradan](https://nodejs.org/download/)    indirebilirsiniz.


2.  Otomatik [kabuk yükleyiciyi ](https://github.com/taaem/nodejs-linux-installer/releases) de kullanabilirsiniz. 


3. Terminali açıp 
<pre><code>
sudo apt-get update
sudo apt-get install nodejs npm</code></pre> yazabilirsiniz.




**Yapılandırma**
<pre><code>tar zxf node-v0.12.2.tar.gz
cd node-v0.12.2
./configure && make && sudo make install</code></pre>



**Mac**


1. Node.js in **.pkg.** uzantılı son versiyonunu [buradan](https://nodejs.org/download/)    indirebilirsiniz.

2. Terminal'i açıp önce <pre><code>brew install node<code></pre> yazabilirsiniz.


**Homebrew kurulumu**

* Önce terminali açınız.

<pre><code>ruby -e "$(curl -fsSL https://raw.githubusercontent.
com/Homebrew/install/master/install)"
</pre>



**Windows**

1. Node.js in **.msi.** uzantılı son versiyonunu [buradan](https://nodejs.org/download/) indirebilirsiniz.
Ardından terminal kullanmak için [git bash](http://git-scm.com/) indirip kurmalısınız.



**Test**

* Terminal'i açınız.
<pre><code>node -v</code>
<code>npm -v</code></pre>






