---
title: Oxidando ecosistemas.
info: |
  ¿Cómo Rust puede potenciar ecosistemas enteros?
background: "#faf3e1"
class: flex flex-col justify-center items-center text-center h-full
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
---
