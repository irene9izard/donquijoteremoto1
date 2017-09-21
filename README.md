# donquijoteremoto1
# Practica Don Quijote - Respuestas

--

**1. ¿Qué comando utilizaste en el paso 11? ¿Por qué?**

`git reset --hard HEAD~1` 

Porque de este modo consigo borrar de forma permanente el último commit.

--

**2. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

`git reflog y git reset --hard 2ed94db` 

Mediante el git reflog localizo el identificador del último commit para después hacer git reset --hard y adjuntarlo y así volver a él.

--

**El merge del paso 13, ¿Causó algún conflicto? ¿Porqué?**

No se produce ningún conflicto porque los cambios que se habían realizado en don quijote se eliminaron del working copy aunque luego se rehizo el último commit.

--

**El merge del paso 19, ¿Causó algún conflicto? ¿Porqué?**

Se produce un conflicto en el archivo don quijote, ya que está guardado de forma diferente en cada rama.

--

**El merge del paso 21, ¿Causó algún conflicto? ¿Porqué?**

No se produce ningún conflicto ya que los problemas han sido resueltos.

--

**¿Qué comando o comandos utilizaste en el paso 25?**

`git graph`

Utilizo git graph para ver el dibujo gráfico.

--

**El merge del paso 26, ¿Podría ser fastforward? ¿Porqué?**

Sí, porque no se encuentra en una bifurcación de ramas.

--

**¿Qué comando ocomandos utilizaste en el paso 27?**

`git reset HEAD~1`
--

**¿Qué comando o comandos utilizaste en el paso 28?**


--

**¿Qué comando o comandos utilizaste en el paso 29?**

`git branch -D title`
--

**¿Qué comando o comandos utilizaste en el paso 30?**

`git reflog y git reset --hard 5763e04`
--

**¿Qué comando o comandos utilizaste en el paso 32?**

`git reflog y git checkout 407bf15`
--

**¿Qué comando o comandos utilizaste en el paso 33?**


`git reflog y git checkout 5763e04
`
