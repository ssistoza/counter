# Counter

A simple GET counter with name and hit count of api.

## Request Parameters:

### name

- Type: string
- Default Value: 'default'
  The name of counter, when no name is matched a new counter is made with the name and the count begins at 1.

### simulate

- Type: boolean
- Default Value: false
  Add one to count, when false and persist change.
  When true, does not persist the additional count as one.

## reset

- Type: boolean
- Default Value: false
  Resets count back to zero if true.
