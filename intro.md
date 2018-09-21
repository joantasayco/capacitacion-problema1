#Paso 2
**¿Qué es integración continua?**
es un modelo informático propuesto inicialmente por Martin Fowler que consiste en hacer integraciones automáticas de un proyecto lo más a menudo 
posible para así poder detectar fallos cuanto antes. Entendemos por integración la compilación y ejecución de pruebas de todo un proyecto.

**¿Para qué sirve DevOps?**
DevOps es una metodología de trabajo basada en el desarrollo de código que usa nuevas herramientas y prácticas para reducir la 
tradicional distancia entre técnicos de programación y de sistemas. Este nuevo enfoque de colaboración que es DevOps permite a los equipos 
trabajar de forma más cercana, aportando mayor agilidad al negocio y notables incrementos de productividad.


**1. ¿Para qué ayuda el `git stash`?**
   Para guardar temporalmente los cambios en la rama. 

**2. ¿Cuál es la diferencia entre `git stash pop` y `git stash apply`?**
    
	git stash pop: aplica los cambios al commit especificado y borra el stash
	
	git stash apply: solo aplica cambios.

**3. ¿Qué significa el modo interactivo del `git rebase`?**
    El rebase interactivo te deja definir precisamente como cada commit será movido hacia la nueva base. 
	Esto te da la oportunidad de limpiar la historia de una rama de característica nueva antes de compartirla con otros desarrolladores.

**4. ¿Cual es la diferencia entre la shell y la terminal?**
    
	Terminal es un punto de conectividad (hardware) que me permite comunicarse con un computador central (servidor)
	Shell: La shell es la interfaz de línea de comandos con la que interactúas y Terminal es un puno de conectividad (harddware) que permite comunicarse con un computador central (servidor)
	

**5. ¿Que hace estos comandos? `git clone`, `git status`, `git add`, `git commit`, `git push`, `git checkout`, `git stash`, `git rebase`, `git merge`, `git branch`, `git push`**

    gi clone: clona un repositorio
	git status: lista el estado del repositorio
	git add: prepara los cambios y agrega al Stage
	git commit: confirma los cambios en Stage
	git push: sube los cambios al repositorio de la rama actual
	git checkout: permite cambiar de rama
	git stash: permite guardar temporalmente los cambios
	git rebase: permite organizar los commits de una rama
	git merge: permite fusionar cambios entre ramas.
	git branch: permite crear una rama