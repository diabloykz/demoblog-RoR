# README
[![Gem](https://img.shields.io/gem/v/rails.svg)](https://rubygems.org/gems/rails) 

Working on Linux Ubuntu here: 

<h3>Ruby version : Ruby v2.6.2</h3><br>
<p>Check your version of Ruby <br>
<code>ruby -v </code> <br>
If you don't have on installed , get yours here https://www.ruby-lang.org/en/documentation/installation/ <br>
</p>

<h3>Configuration</h3> <br>
<h4>Update of tools</h4> <br>
<p><code> sudo apt-get update </code> <br>
<code>sudo apt-get install build-essential libffi-dev libssl-dev libreadline-dev zlib1g-dev libsqlite3-dev </code> <br>
<code>sudo apt-get install nodejs</code> <br></p>

<h4>rbenv and Rails install </h4> <br>
<p><code> git clone https://github.com/sstephenson/rbenv.git ~/.rbenv
echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bashrc
echo 'eval "$(rbenv init -)"' >> ~/.bashrc
git clone https://github.com/sstephenson/rbenv-gem-rehash.git ~/.rbenv/plugins/rbenv-gem-rehash
git clone https://github.com/sstephenson/ruby-build.git ~/.rbenv/plugins/ruby-build
source ~/.bashrc
</code> <br>
<h4>Ruby Install with rbenv</h4>
<code rbenv install 2.6.2
rbenv global 2.6.2 </code><br>
<h4>Bundle install</h4> <br>
This installs all the gems required
  <code>bundle install</code></p>
<h3>Database creation</h3>
  <code>rake db:migrate</code>

<h2>Launch the app </h2>
  <code>bin/rails server</code>

