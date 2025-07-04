
### 📄 `Card.md`

```md
# 💳 Card Component

`Card` is a Material Design surface that presents content with elevation and rounded corners.

---

## 🛠️ Usage

```kotlin
Card {
    Text("Inside a card")
}
````

---

## 📌 Parameters

| Parameter         | Type           | Description                                     |
| ----------------- | -------------- | ----------------------------------------------- |
| `modifier`        | `Modifier`     | Apply size, padding, background.                |
| `shape`           | `Shape`        | Shape of the card (e.g., `RoundedCornerShape`). |
| `elevation`       | `Dp`           | Elevation (shadow).                             |
| `backgroundColor` | `Color`        | Background color of the card.                   |
| `contentColor`    | `Color`        | Content color inside the card.                  |
| `border`          | `BorderStroke` | Border around the card.                         |

---

## 💡 Example

```kotlin
Card(
    shape = RoundedCornerShape(16.dp),
    elevation = 8.dp,
    modifier = Modifier.padding(16.dp)
) {
    Column(modifier = Modifier.padding(16.dp)) {
        Text("Card Title", fontWeight = FontWeight.Bold)
        Text("Card content goes here.")
    }
}
```

---

## 🖼️ Preview

```kotlin
@Preview
@Composable
fun PreviewCard() {
    Card(elevation = 4.dp) {
        Text("Sample Card", modifier = Modifier.padding(16.dp))
    }
}
```

```

---

Would you like me to proceed with the next ones: `Button`, `Image`, or `TextField`?
```
