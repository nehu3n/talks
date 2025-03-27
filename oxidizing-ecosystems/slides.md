---
title: Oxidando ecosistemas.
favicon: /janky_crab.webp
info: |
  ¿Cómo Rust puede potenciar ecosistemas enteros?
background: "#faf3e1"
class: flex flex-col justify-center items-center text-center h-full
transition: slide-down
---

<div class="text-4xl font-black text-black tracking-wide decoration-orange decoration-4 underline underline-offset-4">
  Oxidando Ecosistemas 🦀 🚀
</div>

<div class="text-lg text-gray-900 mt-4 max-w-xl">
  Descubre cómo <span class="text-orange-600 font-semibold">Rust</span> impulsa otros ecosistemas,
  explorando sus ventajas y su impacto en el desarrollo moderno.
</div>

<div class="mt-6 text-gray-700 text-sm">
  Por <span class="font-bold">Nehuén</span> - en colaboración con:
</div>

<div class="flex justify-center items-center gap-6 mt-4">
  <img src="/rustlanges_logo.svg" class="h-20 w-auto" alt="RustLangES Logo" />
  <img src="/universidadnur_logo.png" class="h-28 w-auto" alt="Universidad NUR Logo" />
</div>

---
class: bg-[#faf3e1]
transition: slide-right
---

<div class="text-4xl font-black text-black tracking-wide decoration-orange decoration-4 underline underline-offset-4">
    ¿Quién soy?
</div>

<ul class="list-disc mt-3 mb-3 text-black pl-8 text-lg leading-relaxed">
  <li>👋🏻 Me llamo <span class="font-bold">Nehuén</span></li>
  <li>🦀 <span class="font-semibold text-orange-600">Desarrollador y enjoyer de Rust</span></li>
  <li>⚡️ Apasionado por la programación de alto rendimiento y ecosistemas sostenibles</li>
  <li>😅 Entusiasta en reinventar la rueda</li>
</ul>

<div class="max-w-lg bg-[#27272a] text-gray-100 rounded-lg p-2 shadow-lg text-sm">

```rust
trait Presentacion {
    fn presentarse(&self) -> String;
}

struct Rustacean;

impl Presentacion for Rustacean {
    fn presentarse(&self) -> String {
        "Hola, ¡los saludo desde Rust! 🦀".to_string()
    }
}

fn main() {
    println!("{}", Rustacean.presentarse());
}
```

</div>

---
class: bg-[#faf3e1] h-full
transition: slide-up
---

<div class="justify-center flex flex-col items-center text-center">
  <h2 class="text-5xl font-black text-black tracking-wide decoration-orange decoration-4 underline underline-offset-4">
    ¿Qué es Rust?
  </h2>
  <p class="mt-4 text-xl text-gray-800 max-w-2xl">
    Rust es un lenguaje de programación de sistemas diseñado para ser seguro, rápido y concurrente,
    sin sacrificar el control sobre la memoria.
  </p>
</div>

<v-clicks>
  <div class="mt-6 flex items-center gap-3 justify-center text-black">
    <img src="/ferris_secure.png" class="h-8 w-8" alt="Ferris secure" />
    <span class="font-semibold text-lg leading-snug"><span class="text-orange-600">Memoria segura</span> sin necesidad de un Garbage Collector</span>
  </div>

  <div class="flex items-center gap-3 justify-center text-black">
    <img src="/ferris_ok.png" class="h-8 w-8" alt="Ferris ok" />
    <span class="font-semibold text-lg leading-snug"><span class="text-orange-600">Excelente rendimiento</span> y cero costos de abstracción</span>
  </div>

  <div class="flex items-center gap-3 justify-center text-black">
    <img src="/ferris_love.png" class="h-8 w-8" alt="Ferris love" />
    <span class="font-semibold text-lg leading-snug"><span class="text-orange-600">Un ecosistema robusto</span> con una <span class="text-orange-600">comunidad increíble</span></span>
  </div>
</v-clicks>


<div class="mt-14 bg-[#27272a] text-gray-100 rounded-lg p-2 shadow-lg text-sm max-w-sm mx-auto">

```rust
fn main() {
    println!("¡Hola desde Rust! 🚀");
}
```

</div>

<div class="absolute right-0 bottom-0">
    <img src="/ferris_hi.webp" alt="Ferris greeting" class="h-32 w-auto" />
</div>

---
class: bg-[#faf3e1] h-full
transition: slide-down
---

<div class="flex flex-col items-center text-center">
  <h2 class="text-5xl font-black text-black tracking-wide decoration-orange decoration-4 underline underline-offset-4">
    Filosofía de Rust 🦀 vs. C/C++ 🔧
  </h2>
  <p class="mt-4 text-xl text-gray-800 max-w-3xl">
    Rust adopta la filosofía de <span class="text-orange-600 font-semibold">dejar que el compilador haga el trabajo</span>,
    eliminando errores comunes de memoria y brindando mayor seguridad sin sacrificar rendimiento.
  </p>
</div>

<div class="flex justify-center items-center gap-12 mt-8">

  <div class="flex flex-col items-center text-center max-w-sm">
      <img src="/c_cpp_logos.png" class="h-16 w-auto mt-5" alt="C/C++ Logos" />
    <h3 class="text-2xl font-semibold mt-4 text-gray-900">C / C++</h3>
    <ul class="list-disc mt-3 text-gray-800 text-lg text-left pl-6 leading-relaxed">
      <li>🚨 El programador gestiona la memoria manualmente</li>
      <li>🛠 Posibilidad de <span class="text-red-600">segfaults</span> y <span class="text-red-600">memory leaks</span></li>
      <li>⚠️ Mayor margen de error en concurrencia</li>
    </ul>
  </div>

  <div class="flex flex-col items-center text-center max-w-sm">
    <img src="/rust_logo.svg" class="h-24 w-auto -mt-10" alt="Rust Logo" />
    <h3 class="text-2xl font-semibold mt-4 text-gray-900">Rust</h3>
    <ul class="list-disc mt-3 text-gray-800 text-lg text-left pl-6 leading-relaxed">
      <li>🔒 El <span class="text-orange-600">compilador</span> maneja la memoria por vos</li>
      <li>✅ Seguridad garantizada en tiempo de compilación</li>
      <li>⚡️ Concurrencia sin <span class="text-green-600">data races</span></li>
    </ul>
  </div>

</div>

---
class: bg-[#faf3e1] h-full
transition: slide-right
---

<div class="flex justify-center items-center h-full text-gray-100 rounded-lg p-2 text-sm max-w-sm mx-auto">

````md magic-move
```c
#include <stdio.h>
#include <stdlib.h>

int main() {
    // Crear un array dinámico de 10 enteros
    int *arr = (int *)malloc(10 * sizeof(int));

    if (arr == NULL) {
        printf("No se pudo asignar memoria\n");
        return 1;
    }

    // Inicializar el array
    for (int i = 0; i < 10; i++) {
        arr[i] = i * 2;
    }

    // Imprimir el array
    for (int i = 0; i < 10; i++) {
        printf("%d ", arr[i]);
    }
    printf("\n");

    // Olvidamos liberar la memoria, lo que podría provocar un memory leak
    // free(arr); // Esto debería estar acá, ¡un error humano!

    return 0;
}
```
```rust
fn main() { // Función de Rust
    // Crear un array dinámico de 10 enteros
    int *arr = (int *)malloc(10 * sizeof(int));

    if (arr == NULL) {
        printf("No se pudo asignar memoria\n");
        return 1;
    }

    // Inicializar el array
    for (int i = 0; i < 10; i++) {
        arr[i] = i * 2;
    }

    // Imprimir el array
    for (int i = 0; i < 10; i++) {
        printf("%d ", arr[i]);
    }
    printf("\n");

    // Olvidamos liberar la memoria, lo que podría provocar un memory leak
    // free(arr); // Esto debería estar acá, ¡un error humano!

    return 0;
}

```
```rust
fn main() { // Función de Rust
    // Crear un array dinámico de 10 enteros
    let mut arr: Vec<i32> = Vec::with_capacity(10);

    // Inicializar el array
    for (int i = 0; i < 10; i++) {
        arr[i] = i * 2;
    }

    // Imprimir el array
    for (int i = 0; i < 10; i++) {
        printf("%d ", arr[i]);
    }
    printf("\n");

    // Olvidamos liberar la memoria, lo que podría provocar un memory leak
    // free(arr); // Esto debería estar acá, ¡un error humano!

    return 0;
}
```
```rust
fn main() { // Función de Rust
    // Crear un array dinámico de 10 enteros
    let mut arr: Vec<i32> = Vec::with_capacity(10);

    // Inicializar el array
    for i in 0..10 {
        arr.push(i * 2);
    }

    // Imprimir el array
    for (int i = 0; i < 10; i++) {
        printf("%d ", arr[i]);
    }
    printf("\n");

    // Olvidamos liberar la memoria, lo que podría provocar un memory leak
    // free(arr); // Esto debería estar acá, ¡un error humano!

    return 0;
}
```
```rust
fn main() { // Función de Rust
    // Crear un array dinámico de 10 enteros
    let mut arr: Vec<i32> = Vec::with_capacity(10);

    // Inicializar el array
    for i in 0..10 {
        arr.push(i * 2);
    }

    // Imprimir el array
    for num in &arr {
        println!("{}", num);
    }

    // Olvidamos liberar la memoria, lo que podría provocar un memory leak
    // free(arr); // Esto debería estar acá, ¡un error humano!

    return 0;
}
```
```rust
fn main() { // Función de Rust
    // Crear un array dinámico de 10 enteros
    let mut arr: Vec<i32> = Vec::with_capacity(10);

    // Inicializar el array
    for i in 0..10 {
        arr.push(i * 2);
    }

    // Imprimir el array
    for num in &arr {
        println!("{}", num);
    }

    // No es necesario liberar memoria explícitamente
    // Rust maneja la memoria automáticamente cuando el array sale de alcance
}
```
````

</div>

---
class: bg-[#faf3e1] h-full
transition: slide-left
---

<div class="flex items-right gap-3 justify-right text-black">
  <span class="text-4xl font-black text-black tracking-wide decoration-orange decoration-4 underline underline-offset-4">¿Por qué Rust en otros ecosistemas?</span>
  <img src="/ferris_think.webp" class="h-8 w-8" alt="Ferris think" />
</div>

<div class="mt-6 text-lg text-right justify-right text-black">
    <p>
    Rust no es solo un lenguaje potente por sí mismo, sino que también <span class="text-orange-600 font-bold">se ha ganado un lugar destacado al integrarse con otros ecosistemas.</span>
    Pero, ¿qué lo hace tan atractivo para lenguajes como JavaScript y Python?
  </p>
</div>


<div class="mt-10 text-md text-black">
    <span v-click class="text-black font-extrabold text-orange-700">✨ No es solo...</span>
    <v-clicks>
        <div class="mt-3 flex text-black">
            - Rendimiento
        </div>
        <div class="flex text-black">
            - Seguridad
        </div>
        <div class="flex text-black">
            - Concurrencia
        </div>
    </v-clicks>
   <div>
   </div>

</div>

<div class="mt-10 text-md text-black">
    <span v-click class="text-black font-extrabold text-orange-700">🚀 Rust facilita!</span>
    <v-clicks>
        <div class="mt-3 flex text-black">
            - Herramientas completas para crear bindings a otros lenguajes (JavaScript, Python, Ruby, Lua...)
        </div>
        <div class="flex text-black">
            - WebAssembly como opción nativa para ejecutar Rust en el navegador y otros entornos
        </div>
        <div class="flex text-black">
            - Adopción gradual y a la necesidad del programador
        </div>
    </v-clicks>
</div>

<div class="absolute right-14 bottom-50">
    <img src="/ferris_web.png" alt="Ferris web" class="h-32 w-auto" />
</div>

---
class: bg-[#faf3e1] h-full
transition: slide-down
---

<div class="text-4xl font-black text-black tracking-wide decoration-orange decoration-4 underline underline-offset-4 mb-12">
    Mientras tanto en el mundo de JavaScript ✨
</div>

<div class="flex space-x-10 mb-12">
    <img v-click src="/deno_logo.png" alt="Deno" class="h-20 w-20 object-contain"/>
    <img v-click src="/rspack_logo.png" alt="Rspack" class="h-20 w-20 object-contain"/>
    <img v-click src="/swc_logo.png" alt="SWC" class="h-20 w-20 object-contain"/>
    <img v-click src="/tailwind_logo.png" alt="Tailwind CSS" class="h-20 w-20 object-contain"/>
    <img v-click src="/oxc_logo.png" alt="Oxc" class="h-20 w-20 object-contain"/>
</div>

<div class="mt-6 text-lg text-black">
    <p>
        El ecosistema de <span class="text-orange-600 font-bold">JavaScript</span> está siendo cada vez más impulsado por tecnologías basadas en <span class="text-orange-600 font-bold">Rust</span>, lo que permite una mejora significativa en el rendimiento y la eficiencia de los proyectos.
    </p>
</div>

<div class="flex space-x-10 mb-12 mt-12">
  <div v-click>
    <img src="/napirs_logo.png" alt="NapiRs" class="h-20 w-20 mb-1 object-contain"/>
    <span class="text-orange-600 font-extrabold text-center justify-center ml-1 mt-3 text-lg leading-snug">Napi-RS</span>
  </div>
  <div v-click>
    <img src="/wasm_logo.png" alt="WebAssembly" class="h-20 w-20 mb-1 object-contain"/>
    <span class="text-violet-600 font-extrabold -ml-5 text-lg leading-snug">Web Assembly</span>
  </div>
</div>

<div class="absolute -right-10 -bottom-5">
    <img src="/carcinologo.png" alt="Carcino logo" class="h-32 w-auto" />
</div>

---
class: bg-[#faf3e1] h-full
transition: slide-left
---

<div class="justify-center flex flex-col items-center text-center">
  <h2 class="text-5xl font-black text-black tracking-wide decoration-orange decoration-4 underline underline-offset-4">
      Napi RS
  </h2>
  <p class="mt-4 text-xl text-gray-800 max-w-xl">
      NapiRS es una librería para crear módulos de JavaScript aprovechando las ventajas de Rust.
  </p>
</div>

<div class="flex space-x-5 mt-5">
  <div class="w-1/2">
    <div class="bg-[#27272a] p-2 rounded-lg text-white">

```rust
// Fácil y rápido!
use napi_derive::napi;

#[napi]
pub fn sum(a: u32, b: u32) -> u32 {
    a + b
}
```
    </div>
  </div>

  <div class="w-1/2">
    <div class="bg-[#27272a] p-2 rounded-lg text-white">

```typescript
import { sum } from './index.js'

console.log(sum(2, 2)); // 4

// Genera tipos automaticamente!
const result = sum(3, "hola");  // Error de TypeScript
console.log(result);
```
    </div>
  </div>
</div>

<div class="justify-center flex items-center mt-10">
    <img src="/ferris_headpat.gif" alt="Ferris headpat" class="h-32 w-auto" />
</div>

---
class: bg-[#faf3e1] h-full
---

<div class="justify-center flex items-center">
  <img src="/kito_banner.png" alt="Kito banner" class="h-32 w-auto" />
</div>

<div class="justify-center flex items-center">
  <p class="mt-2 text-md text-gray-800 max-w-lg text-center">
    Kito es un framework web backend de alto rendimiento para TypeScript, escrito en Rust.
  </p>
</div>

<div class="mt-3 text-md max-w-lg justify-center flex items-center mx-auto">

```typescript
import { server } from 'kitojs';

const app = server();

app.get('/', (req, res) => {
  res.send('Hello, world!');
});

app.listen(3000);
```

</div>

---
class: bg-[#faf3e1] h-full
transition: slide-right
---

<div class="flex justify-center items-center h-full mx-auto">
  <img src="/kito_bench.png" alt="Kito benchmark" class="h-[400px]" />
</div>

<div class="absolute right-0 bottom-0">
    <img src="/swalla.gif" alt="Swalla" class="h-20 w-auto" />
</div>

---
class: bg-[#faf3e1] h-full
---
