# rtd

Manage your todo in command line with `rtd` (Rust To Do)

## Features
**Add a todo**

```
// Add a new to-do to inbox as low priority
rtd add "This is a todo" ~inbox !low 
```

**List todo**
```
# list all todo not done yet
rtd list 

# list completed todo
rtd list --done

# list all

rtd list --all
```

**Today's priority**
```
// Mark a todo as your today's priority
rtd today <todo-id>

// Unmark a todo from your today's priority by prefix it with a ~
rtd today ~<todo-id>
```

**Complete task**

```
// mark task as done
rtd done <task-id>

// mark task as not done by prefix task id with a ~
rtd done ~<task-id>
```