# Instalar Pytyle en Debian


### Download Page for pytyle_0.7.5-4_all.deb
### If you are running Debian, it is strongly suggested to use a package manager like aptitude or synaptic to download and install packages, instead of doing so manually via this website.

1. Open a terminal and install apt-transport-https

`sudo apt-get install apt-transport-https`

2. Add this line to your /etc/apt/sources.list :

`deb https://notesalexp.org/debian/jessie/ jessie main`

3. Fetch and install the GnuPG key

`sudo apt-get update -oAcquire::AllowInsecureRepositories=true`

`sudo apt-get install notesalexp-keyring -oAcquire::AllowInsecureRepositories=true`

`sudo apt-get update`

or

`wget -O - https://notesalexp.org/debian/alexp_key.asc | sudo apt-key add -`

`sudo apt-get update`

4. Enjoy

`sudo aptitude install pytyle`

- You can download the requested file from the pool/main/p/pytyle subdirectory at this link:

[Enlace de Descarga](https://notesalexp.org/jessie/main/p/pytyle/pytyle_0.7.5-4_all.deb)
