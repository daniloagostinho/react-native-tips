# react-native-tips
tips of react 

#### Erro watch 

Solucao

- $ git clone https://github.com/facebook/watchman.git
- $ cd watchman
- $ git checkout v4.7.0
- $ ./autogen.sh
- $ ./configure
- $ make
- $ sudo make install

- $ chmod 0700 /usr/local/var/run/watchman/<user>-state
  
  
  [referencia](https://stackoverflow.com/questions/40414166/react-native-npm-start-with-watchman-error/40441481)
