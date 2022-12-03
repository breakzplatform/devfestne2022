# Você (provavelmente) não sabia que o Chrome DevTools tinha isso
	🐦 @breakzplatform
	🐘 @eu@joseli.to
/assets/DncJWGy.webp
size: contain
x: right
y: bottom
---
# console
	além do log()
---
## console.log("❤️")
---
```
console.log()
console.info() // ℹ️
console.warn() // ⚠️
console.error() // 🛑
```
---
```
console.log()
console.info() // ℹ️
console.warn() // ⚠️
console.error() // 🛑
console.???() // 📝
console.???() // 👩‍👩‍👦‍👦
console.???() // 🧮
console.???() // 🔢
console.???() // ⌚️
console.???() // 🔍
```
---
```
// montagem de string estilo C
console.log('%i %s foram passear', 5, 'patinhos');

// loga PI => 3.141592653589793
console.log(Math.PI); 

// loga PI como inteiro
console.log('%i', Math.PI); 

// loga o body como nó do DOM
console.log('%o', document.body); 

// loga o body como objeto
console.log('%O', document.body); 
```
---
```
// log_s()
console.log("%cCuidado!", "font-size: 4rem;font-weight:700;color:red;text-transform: uppercase;");
```
---
```
// wh_0()
console.log(width)
console.log(height)
```
---
```
// wh_1()
console.log({width})
console.log({height})

// wh_2()
console.log({width, height})
```
---
## console.debug()
---
## console.dir()
---
## 👁️
---
## ⚙️
---
## filtros

-/globo.com/
---
## console.table()
---
```
// todos elementos h1, p e script
let contentElements = document.querySelectorAll(':is(h1,p,script)');

// exibe os elementos como tabema
console.table(contentElements);
// exibe apenas os conteúdos relevantes 
console.table(contentElements, ['nodeName','innerText','offsetHeight']);
```
---
## console.group()
---
```
// g_1()
console.group("Passengers: Heart of Gold");
console.log('Zaphod');
console.log('Trillian');
console.log('Ford');
console.log('Arthur');
console.log('Marvin');
console.groupCollapsed("Hidden");
console.log('(Frankie & Benjy)');
console.groupEnd("Hidden");
console.groupEnd("Passengers: Heart of Gold");

// g_2()
let technologies = {
  "Standards": ["HTML", "CSS", "SVG", "ECMAScript"],
  "Others": ["jQuery", "Markdown", "Textile", "Sass", "Pug"]
}

for (tech in technologies) {
  console.groupCollapsed(tech);
  technologies[tech].forEach(t => console.log(t));
  console.groupEnd(tech);
}
```
---
## console.count()
---

```
for (let i = 0; i < 10; i++){
  console.count()
}
```
---
```
let user = "";

function greet() {
  console.count(window.user);
  return `oi ${window.user}`;
}

user = "bianca";
greet();
user = "eduardo";
greet();
greet();
console.count("bianca");

console.countReset("eduardo");

// gr_9()
```

---
## console.timer()
---
```
// ct_0()
console.time();

setTimeout(() => {
  console.timeEnd();
}, 5000);
```
---
```
// ct_1()
console.time();

setTimeout(() => {
  console.timeEnd();
}, 5000);

setTimeout(() => {
  console.timeLog()
}, 2000);
```
---
## console.trace()
---
	console.log("entrou");
	console.log("aqui, x:", x);
	console.log("teste");
---
```
// tr_0()
function essa() {
  aquela();
}

function aquela() {
  outra();
}

function outra() {
  console.trace();
}

essa();
```
---
## console.assert()
---
```
console.assert(true, "Eu não apareço");
console.assert(false, "Eu sim");
```
---
```
// as_0()

const errorMsg = "# não é impar!";

for (let number = 2; number <= 13; number++) {
  console.log(`número ${number}`);
  console.assert(number % 2 != 0, '%o', { number, errorMsg });
}
```
---
## $
---
	- $()
	- $$()
	- $0-$4
	- $_
---
## copy()
---
## debug()
---
## monitor()
---
```
window.sum = (x, y) => x + y;

monitor(window.sum)l
// mo_0()
```
---
## monitorEvents()
---
```
monitorEvents(window, ["resize", "scroll"]);
```
---
## inspect()
---
# command palette
	⌘ + ⇧ + p
---
# sources
---
## open
	⌘ + p
---
## snippets
---
## overrides
---
# obrigado 🤗
## joseli.to
### 🐦 @breakzplatform
### 🐘 @eu@joseli.to