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
