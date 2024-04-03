# Grace ToDo App

### Kratek opis

Aplikacija bo pomagala uporabniku z beleženjem opravil. Uporabnik bo lahko dodajal, urejal in brisal opravila. Opravila bo lahko tudi označil kot opravljena.

Končno rešitev si lahko pogledate [tukaj](https://grace-todo.vercel.app/).

### Struktura

Aplikacijo bodo sestavljale naslednje komponente:

1. `App.jsx`: Ta bo hranila seznam vseh todo objektov. Prikazala `ShowTodos.jsx` in `AddTodo.jsx`
2. `AddTodo.jsx` bo prikazala `form` za dodajanje novega todo objekta
3. `ShowTodos.jsx` bo prikazala vse todo-je v 2 stolpcih: "Opravljeni" in "Neopravljeni"
4. `Todo.jsx` bo prikazal izkaznico enega todo-ja. `ShowTodos.jsx` bo z njim prikazal seznam vseh todo-jev.

## Navodila

### I. Seznam todojev

1. V `App.jsx` definirajte `todos` state, ki bo hranil seznam vseh todo objektov. Na začetku naj bo seznam prazen.
2. V `App.jsx` definirajte funkcijo `addTodo`, ki bo sprejela `todo` objekt in ga dodala v seznam `todos`.

### II. Dodajanje todojev

1. V `AddTodo.jsx` definirajte state: `title`. Na začetku naj bo prazen string.
2. Naredite `form` in vanj dodajte `Input` polje, ki bo uporabniku omogočilo vnos naslova todo-ja. Input "povežite" s state-om `title`.
