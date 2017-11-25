<p align="center">
  <img src="https://raw.githubusercontent.com/lord/img/master/logo-slate.png" alt="Slate: API Documentation Generator" width="226">
  <br>
</p>

<p align="center">This repository contains the Slate-based Oraclize documentation. You can check it out @ <a href="https://docs.oraclize.it">docs.oraclize.it</a>.</p>
<h3>INSTRUCTIONS FOR Ubuntu 16.04 LTS (Xenial Xerus)</h3>
<p>Slate requires some libries as follow</p>
<ul>
	<li>sudo apt-get install ruby-dev zlib1g-dev curl</li>
	<li>curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash - && sudo apt-get install -y nodejs</li>
	<li>sudo gem install bundler</li>
</ul>

<p> NOW WITH THE DEPENDENCIES INSTALLED YOU CAN RUN THE BUNDLER </p>
<ul>
 	<li>bundler install --path vendor/bundle</li>
 	<li>bundler exec middleman server</li>
</ul>

 
 
 


