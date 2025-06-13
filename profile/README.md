# Styx API Generator

**Create type-safe wrappers for command line tools**

Transform any command-line tool into a type-safe programming interface. Originally built for neuroimaging research, Styx generates Python, TypeScript, and R bindings from structured tool descriptions.

## Key Projects

🧠 **[niwrap](https://github.com/styx-api/niwrap)** - Modern neuroimaging made simple  
🔧 **[styx](https://github.com/styx-api/styx)** - Core compiler for generating tool wrappers  
📚 **[styxbook](https://github.com/styx-api/styxbook)** - Complete documentation and guides  

## Quick Start

```python
# Instead of: bet input.nii output.nii -f 0.5 -m
from niwrap import fsl
outputs = fsl.bet(infile="input.nii", fractional_intensity=0.5, mask=True)
```

**[📖 Read the docs](https://styx-api.github.io/styxbook/)** • **[🐛 Report issues](https://github.com/styx-api/niwrap/issues)** • **[💬 Get help](https://github.com/styx-api/niwrap/discussions)**
