# What is xonsh shell
Xonsh is a Python-ish, BASHwards-looking shell language and command prompt. The language is a superset of Python 3.4+ with additional shell primitives that you are used to from Bash and IPython. It works on all major systems including Linux, Mac OSX, and Windows. Xonsh is meant for the daily use of experts and novices alike.
Please visit http://xon.sh for more information.

# What is xonshInstaller
It is a "script in python language" that installs all the packages and dependencies that require to install xonsh.

Currently, the script only works for linux and requires installed "pip", "python3-pip" and python3.4+

# Instalation
As root user:
```sh
   ~# wget -O - http://css.co.ve/xonshInstaller | python3
```
As sudo user:
```sh
   ~$ wget -O - http://css.co.ve/xonshInstaller | sudo python3
```
And done.   
If you want change you default shell, run
```sh
  ~$ chsh -s $(which xonsh)
```
Or if you want to try conch shell, run
```sh
  ~$ xonsh
```
