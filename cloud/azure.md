## common errors 

### could nt start storage emulator 

this is mostly due to the a **another software using port 10000**.
to resolve :
- find programme using port 10000 by - ```netstat -p tcp -ano | findstr :10000```

- run **terminal** in **admin mode** and kill process - ```taskkill /PID < process-number > /F```
  -for  more info refer   [kill a task](../scripting/powershell#kill-a-task) in powershell doc 