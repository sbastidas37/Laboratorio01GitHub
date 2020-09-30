Laboratorio01 de Git Hub

Hoy estamos aprendiendo Git. Es un repositorio distribuido para el control de código fuente.

Adiciono los parametros del editor global de textos de Git.

Path notepad++:

	$ git config --global core.editor "'C:\Program Files\Notepad++' -multiInst -notabbar -nosession -noPlugin"
	$ start notepad++ readme.txt
	$ alias np++ = 'start notepad++.exe'
	$ np++ <filename>
	
	Primera modificacion despues de hacer commit (tenerlo en el repositorio local).
	
	Segunda modificacion despues de hacer el Add (Es decir, despues de tenerlo en el Stagin Area)
	
	Tercera modificacion