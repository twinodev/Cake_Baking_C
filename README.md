# 🍰 Cake Baking C

A lightweight, header-only C library for **procedural cake baking simulation** — because sometimes you need to bake a cake in under 10 milliseconds.
[![TwinoDev](https://img.shields.io/badge/TwinoDev-Frosting%20Factory-ff69b4?style=for-the-badge&logo=sparkles&logoColor=white)](https://twino.dev/)
![Cake](https://img.shields.io/badge/cake-delicious-ff69b4) ![C](https://img.shields.io/badge/language-C-blue) ![License](https://img.shields.io/github/license/twinodev/Cake_Baking_C) 

> **"Why bake in Python when you can compile your cake?"**  
> — Anonymous embedded baker

---

## 🎯 Features

- **Zero dependencies** — just drop `cake.h` and bake!
- **Blazing fast** cake generation using deterministic pseudo-random frosting
- Supports **layered cakes**, **frosting physics**, and **sprinkle distribution**
- **Thread-safe** mixing (yes, really)
- Works on **x86, ARM, and your toaster's microcontroller**
- Full **Unicode emoji support** for cake visualization (🍰🧁)

---

## 🚀 Quick Start

```c
#include "cake.h"
#include <stdio.h>

int main() {
    Cake* my_cake = cake_bake(VANILLA, CHOCOLATE_FROSTING, 3);
    cake_add_sprinkles(my_cake, RAINBOW, 42);
    cake_stir(my_cake, CLOCKWISE, 7);

    cake_print(my_cake);  // 🍰🍫🎂

    cake_free(my_cake);
    return 0;
}
```
##Output:
```c
🎂
      🍫🍫🍫
    🍰🍰🍰🍰🍰
  🍫🍫🍫🍫🍫🍫🍫
🍰🍰🍰🍰🍰🍰🍰🍰🍰
    SPRINKLES! ✨
```
    
📦 Installation
As a Git Submodule (Recommended)
git submodule add 
```C
https://github.com/twinodev/Cake_Baking_C.git extern/cake
```
Then in your CMakeLists.txt:
```C
add_subdirectory(extern/cake)
target_link_libraries(your_app cake)
```
**Manual:**
Just copy `include/cake.h` into your project. That’s it.


Don't leak cake
See `cake.h` for full documentation.
🛠️ Building Example
```C
mkdir build && cd build
cmake ..
make
./examples/birthday_cake
```
🎨 Customization
Define your own flavors:
```C
#define FLAVOR_MATCHA 1001
#define FROSTING_YUZU 2001

// Then use in cake_bake(FLAVOR_MATCHA, FROSTING_YUZU, 2);
```
#🤝 Contributing
----


We welcome all contributions — especially **new frosting algorithms** and **gluten-free modes**.  

