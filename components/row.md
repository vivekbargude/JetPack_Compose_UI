### 📄 `Row.md`

```md
# 📏 Row Component

`Row` arranges children horizontally in a single line.

---

## 🛠️ Usage

```kotlin
Row {
    Text("First")
    Text("Second")
}
````

---

## 📌 Parameters

| Parameter               | Type                     | Description                                                  |
| ----------------------- | ------------------------ | ------------------------------------------------------------ |
| `modifier`              | `Modifier`               | Apply layout styling.                                        |
| `horizontalArrangement` | `Arrangement.Horizontal` | Spacing of items (e.g., `Arrangement.SpaceBetween`).         |
| `verticalAlignment`     | `Alignment.Vertical`     | Align items vertically (e.g., `Alignment.CenterVertically`). |

---

## 💡 Example

```kotlin
Row(
    modifier = Modifier.fillMaxWidth(),
    horizontalArrangement = Arrangement.SpaceEvenly,
    verticalAlignment = Alignment.CenterVertically
) {
    Text("Item 1")
    Text("Item 2")
    Text("Item 3")
}
```

---

## 🖼️ Preview

```kotlin
@Preview
@Composable
fun PreviewRow() {
    Row {
        Text("Row Item")
    }
}
```

````

---