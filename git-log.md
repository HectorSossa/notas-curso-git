### git log

`git log --graph`
`git log --oneline`
`git log --oneline --graph`

mostrar el hitorial de otras formas

`git log -2` ver los ultimos dos commit

`git log --pretty=format:"%h - %an, %ar : %s"` el historial con formato historial - autor, hace cuanto se creo : titulo

mostrar historial apartir de una fecha `git log --after="2016-04-07 00:00:00"`

mostrar historial antes de una fecha `git log --bfore="2016-04-07 00:00:00"`

ambas `git log --after="2016-04-07 00:00:00" --bfore="2016-04-07 11:30:00`

git log --oneline
`nos muestra el historial en una sola linea por el commit`