---
id: queries
title: Queries
ref: docs/framework/solid/guides/queries.md
replace:
  'const info = useQuery(() => { queryKey: ['todos'], queryFn: fetchTodoList })': 'const info = useQuery(() => ({ queryKey: ['todos'], queryFn: fetchTodoList }))'
  'const result = useQuery(() => { queryKey: ['todos'], queryFn: fetchTodoList })': 'const result = useQuery(() => ({ queryKey: ['todos'], queryFn: fetchTodoList }))'
---
