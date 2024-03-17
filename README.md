# DocuSaurus

[&#x213C;](#idxXXX)<br id="idx000"><br>
# ROOT: Install

```
#!/bin/bash
MYUSER="cbkadal"
export DEBS="
aptitude
git
sudo
vim
"
date;
time apt-get install $DEBS -y

```

[&#x213C;](#)<br id="idx001"><br>
## PURGE YARN (JEKYLL)

```
aptitude purge cmdtest


```

[&#x213C;](#)<br id="idx001"><br>
## USER: NVM (node.js)

```
wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash

```

[&#x213C;](#)<br id="idx002"><br>
## Check it out! (E.g. v20.11.1)

```
nvm ls-remote
## E.g. v20.11.1   (Latest LTS: Iron)

```

[&#x213C;](#)<br id="idx002"><br>
## Install and Check Version (e.g. v20.11.1)

```
nvm install v20.11.1
sleep 2
node -v

```

[&#x213C;](#)<br id="idx002"><br>
## YARN

```
npm install -g yarn
sleep 2
yarn --version
# UPDATE
# npm install -g npm@10.5.0

```

[&#x213C;](#)<br id="idx002"><br>
## USER: 

```
npx create-docusaurus@latest Docusaurus classic --typescript

```

[&#x213C;](#)<br id="idx003"><br>

* <https://docusaurus.io/docs/>
* <https://cbkadal.github.io/231saurus/docs/AP01/02/>


[&#x213C;](#)<br id="idxXXX"><br>

<pre><strong>
REV00: Sun 17 Mar 2024 18:00
START: Sun 17 Mar 2024 14:00
</strong></pre>
