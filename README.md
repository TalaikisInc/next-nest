# Next.js vs Nest.js benchmark

is to determine whether try to use Nest.js over Next.js after Next.js comparing same amount of data rendered.

## Methodology

Simple `autocannon http://localhost:3000/`

## Results

### Next.js

```bash
2440.31 rps
4.29 ms
```

### Nest.js

```bash
6119.7 rps
1.24 ms
```

Conclusion. Nest.js is 2.5x faster, but the framework isn't reactive like Next.js/ React.js, so this result will definitely change to much worse after adding some sort of reactivity.
