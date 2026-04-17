# Smurf++
from pathlib import Path
import pypandoc

md_content = """# 🧢 Smurf++ — The Official Smurf Programming Language

> “Why use 100 words when *smurf* does everything?” — Papa Smurf

---

## 🌲 Philosophy

Smurf++ is a context-oriented language where the word **"smurf"** acts as a universal polymorphic unit.  
Everything depends on tone, position, and… a bit of blue magic.

---

## 🧩 Basic Syntax

### Variable Declaration

```smurf
smurf a = smurf;
```

---

### Function

```smurf
smurf smurfify(smurf x) {
    smurf x;
}
```

---

### Condition

```smurf
if (smurf == smurf) {
    smurf;
} else {
    smurf smurf;
}
```

---

### Loop

```smurf
while (smurf) {
    smurf++;
}
```

---

## 🧠 Typing System

| Keyword   | Assumed Type        |
|----------|---------------------|
| smurf    | any                 |
| SMURF    | divine constant     |
| smurf?   | nullable smurf      |
| smurf!   | important smurf     |

---

## 🗣️ Semantic Overloading

```smurf
smurf smurf smurf;
```

Possible meanings:
- declare a variable
- call a function
- insult Gargamel
- order food

---

## 🔥 Exceptions

```smurf
try {
    smurf();
} catch (GargamelException e) {
    smurfAway();
}
```

---

## 📦 Modules

```smurf
import Smurfette;
import PapaSmurf.*;
```

---

## 🧪 Full Example

```smurf
import Village;

smurf main() {
    smurf mood = smurfy;

    if (mood == smurfy) {
        smurf dance();
    } else {
        smurf sulk();
    }

    return smurf;
}
```

---

## 💙 Motto

> "Code less. Smurf more."
"""

output_path = "/mnt/data/smurfplusplus_en.md"

pypandoc.convert_text(md_content, 'md', format='md', outputfile=output_path, extra_args=['--standalone'])

output_path
