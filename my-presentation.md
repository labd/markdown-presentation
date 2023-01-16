class: center, middle, intro

# My presentation

---

## This talk

1. First this
2. Then that

???

My notes

Don't forget to say this.

You will only see this in your presentation view.

---

```tsx
<button className="close">close</button>
```

```scss
:root {
  --icon-close: url("data:image/svg+xml,%3C...");
}

.close {
  font-size: 0; // hide text
  background: gray;
  mask: var(--icon-close) center center / 1.5rem 1.5rem no-repeat;
  transition: all 0.15s ease;
  transform: scale(1);
}
.close:hover {
  background: black;
  transform: scale(1.1);
}
```
