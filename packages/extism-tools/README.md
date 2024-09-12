## Extism Tools

### Prerequisites for Development

- [Extism PDK](https://github.com/extism/js-pdk?tab=readme-ov-file#linux-macos)

### Build WASM files

```bash
pnpm run build
```

### Run WASM files in Node.js using Extism SDK (https://github.com/extism/js-sdk)

```bash
cd examples
pnpm run test
```

### Test using WASM tool with OpenAI Agent

```bash
node examples/tool/wiki.js
```

### Run WASM files in Python using Extism SDK (https://github.com/extism/python-sdk)

```bash
python examples/wasm/wiki.py
```
