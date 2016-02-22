

#Node.js Kurulum

**Linux**


* Node.js in **.tar.gaz.** uzantılı son versiyonunu [buradan](https://nodejs.org/download/)    indirebilirsiniz.

**Yapılandırma**
<pre><code>tar zxf node-v0.12.2.tar.gz
cd node-v0.12.2
./configure && make && sudo make install</code></pre>


*  Otomatik [kabuk yükleyiciyi ](https://github.com/taaem/nodejs-linux-installer/releases) de kullanabilirsiniz. 


* Terminali açıp 
<pre><code>
sudo apt-get update
sudo apt-get install nodejs npm</code></pre> 
yazabilirsiniz.

**Mac**


* Node.js in **.pkg.** uzantılı son versiyonunu [buradan](https://nodejs.org/download/)    indirebilirsiniz.

* Terminal'i açıp önce <pre><code>brew install node</code></pre> yazabilirsiniz.


**Homebrew kurulumu**

* Önce terminali açınız.

<pre><code>ruby -e "$(curl -fsSL https://raw.githubusercontent.
com/Homebrew/install/master/install)"</code></pre>



**Windows**

* Node.js in **.msi.** uzantılı son versiyonunu [buradan](https://nodejs.org/download/) indirebilirsiniz.
Ardından terminal kullanmak için [git bash](http://git-scm.com/) indirip kurmalısınız.



**Test**

* Terminal'i açınız.
<pre><code>node -v 
npm -v </code></pre>





#MongoDB Kurulum

**Linux**

* Önce terminali açıp, mongoDB'nin açık anahtarını sisteme yüklemeniz gerekiyor.

<pre><code> sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv 7F0CEB10
</code></pre>

* **/etc/apt/sources.list.d/mongodb-org-3.0.list** dosyasına aşağıdaki komutu ekleyiniz.

<pre><code>echo "deb http://repo.mongodb.org/apt/ubuntu "$(lsb_release -sc)"/mongodb-org/3.0 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-3.0.list
</code></pre> 

* Sistemi güncelleyiniz.

<pre><code>sudo apt-get update
</code></pre>

* MongoDB paketlerini yükleyiniz.

<pre><code>sudo apt-get install -y mongodb-org
</code></pre>

* MongoDB'nin belirtilen sürümünü yükleyiniz.

<pre><code>sudo apt-get install -y mongodb-org=3.0.2 mongodb-org-server=3.0.2 mongodb-org-shell=3.0.2 mongodb-org-mongos=3.0.2 mongodb-org-tools=3.0.2
</code></pre>

**Windows**

* MongoDB'nin bilgisayarınıza uygun versiyonunu [buradan](http://www.mongodb.org/downloads) indirebilirsiniz.

Not: 64 bit versiyonu 32 bitte çalışmamaktadır.


**Mac**

* Önce homebrew kurmanız gerekli!

* Terminali açınız, aşağıdaki komutu yazınız.

<pre><code>brew install mongodb
</code></pre>

* SSL ekleyiniz

<pre><code>brew install mongodb --with-openssl
</code></pre>

* Başka bir sürüm yüklemek isterseniz

<pre><code>brew install mongodb --devel
</code></pre>

**Homebrew kullanmadan nasıl indiririm?**

* Terminali açınız ve aşağıdaki komutları sırayla yazınız.

<pre><code>curl -O https://fastdl.mongodb.org/osx/mongodb-osx-x86_64-3.0.2.tgz

tar -zxvf mongodb-osx-x86_64-3.0.2.tgz

mkdir -p mongodb

cp -R -n mongodb-osx-x86_64-3.0.2/ mongodb

</code></pre>

* Şimdi PATH'e mongoDB'nin konumunu eklemeniz gerekli.

<pre><code> export PATH=<mongodb-install-directory>/bin:$PATH
</code></pre>


**Homebrew kurulumu**

* Önce terminali açınız.

<pre><code>ruby -e "$(curl -fsSL https://raw.githubusercontent.
com/Homebrew/install/master/install)"</code></pre>








