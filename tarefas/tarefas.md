## Tarefas

### Tarefas concluídas
```tasks
done
```
### Para hoje
```tasks
not done
due today
```
### Para amanhã
```tasks
not done
due tomorrow
```
### Para esta semana
```tasks
not done
due after monday and before friday
```

### Atrasadas
```tasks
not done
due before date(today)
```
### Sem data definida
```tasks
not done
no due date
```

## Outras tarefas

```dataviewjs
dv.taskList(dv.pages('-"Templates"').file.tasks
.where(t => !t.completed && !t.text.includes("@frank") &&
!t.text.includes("#task")
))
```
