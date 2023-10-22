To reproduce the results: - 

1. Create the stack 
```bash
$ ./create-stack.sh <stack-name> infrastructure.yml infrastructure-parameters.json 
```

2. Update the stack (after making a change)
```bash
$ ./update-stack.sh <stack-name> infrastructure.yml infrastructure-parameters.json 
```

3. Delete the stack (to avoid recurring charges)
```bash
$ ./delete-stack.sh <stack-name> 
```