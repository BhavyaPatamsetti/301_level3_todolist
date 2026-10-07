# In-Memory Todo List

A JavaScript exercise that adds sample tasks, marks a task complete, and groups tasks by due date.

## What is included

- Includes `add`, `markAsComplete`, `overdue`, `dueToday`, `dueLater`, and display formatting.

## Getting started

With Node.js installed:

```sh
node index.js
```

The script prints its built-in sample tasks.

## Repository guide

- `README.md`
- `index.js`

## Limitations and reproducibility

Tasks exist only in memory. Overdue and later filters compare specifically with yesterday and tomorrow, rather than handling every earlier or later date. There is no interactive CLI or database.
