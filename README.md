# Counter
A Simple counter with name and hit count of api. 

## Request Parameters:

### name
Type: string
default: 'default'
The name of counter, when no name is matched a new counter is made with the name and the count begins at 1.

### simulate
Type: boolean
default: false
Add one to counter, when false and persist change.
When true, does not persist the additional count as one.
