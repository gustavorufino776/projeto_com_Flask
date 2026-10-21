## projeto com flask





#### como instalar e configurar o uv na sua máquina virtual pelo PowerShell





* utilizamos o comando: (powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex") que pegamos do google;
* após isso utilizamos o prompt: (uv init) para inicializar o uv
* após isso verifique a versão com: (uv -V)
* Se a versão for inferior a 3.15.0 instale utilizando o prompt: (uv python install 3.15.0)
* então inicialize o ambiente virtual colocando: (uv venv)
* para sincronizar com a atualização e o ambiente virtual coloque: (uv sync) feche o vs code e abra novamente
* logo depois utilize o prompt: (uv add Flask) para instalar o micro-framework Flask



#### Utilização do uv em python

* Importamos o Flask para fazer um arquivo em python
* Utilizamos a função (route) para fazer diferentes rotas do cabeçalho de uma URL
* Fizemos uma pasta chamada: Templates para utilizar uma pagina HTML ao invés de só utilizar snippets de código HTML