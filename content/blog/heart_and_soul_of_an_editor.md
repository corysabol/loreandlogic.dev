+++
title = "The Heart and Soul of a Text Editor"
date = 2024-10-29
+++

As a programmer and writer I live and die by my text editing experience. I know how awful it feels for my editor to hang or feel unresponsive.
It's like death by a thousand paper cuts.

Okay, perhaps I am being a bit overly dramatic. But when you spend so much of your limit time on this planet editing various types of text
it is important that it be a great experience.

That is why when I set out to create my own highly specialized text editor called Lore, I knew that I had to do it right. Performance was a must.
Or at least the illusion of performance. Either way the user should not have to wait. They should be able to type into the editor as fast as their fingers can carry them.

So, I set out upon a journey to see what made some of my favorite text editors perform so well. Afterall, a text editor is deceptively complex under the hood.

# Hang on Baby

Enter Ropes. The most common data structure employed be many text editors. Ropes are

**Explanation of rope data structure**

Rope example

```rs
fn foo(s: &str) -> String {
  s.to_string()
}
```

## Benchmarks

## Comparison with Gap Buffer

## Why Ropes instead of Gap Buffer

- Ease of use
- Common
- Developer velocity

# Lore Core
