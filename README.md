- 👋 Hi, I’m Adri
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Adrixy78/Adrixy78 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.

```cpp
#include <iostream>
#include <thread>
#include <chrono>

void dibujarPato(int pasos) {
    for (int i = 0; i < pasos; i++) {
        std::cout << "   __\n";
        std::cout << " /    \\\n";
        std::cout << "| o  o |\n";
        std::cout << " \\_v_/\n";
        std::this_thread::sleep_for(std::chrono::milliseconds(500)); // Pausa de medio segundo
        system("clear"); // Para sistemas Unix-like. En Windows, cambiar a "cls"
    }
}

int main() {
    int numPasos = 5;
    dibujarPato(numPasos);
    
    return 0;
}
```
