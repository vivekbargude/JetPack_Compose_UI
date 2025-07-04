### 📄 `Column.md`

```md
# 📐 Column Component

`Column` arranges children vertically in a single column.

---

## 🛠️ Usage

```kotlin
Column {
    Text("Item 1")
    Text("Item 2")
}
````

---

## 📌 Parameters

| Parameter             | Type                   | Description                                         |
| --------------------- | ---------------------- | --------------------------------------------------- |
| `modifier`            | `Modifier`             | Apply layout or padding.                            |
| `verticalArrangement` | `Arrangement.Vertical` | Spacing of items (e.g., `Arrangement.SpaceAround`). |
| `horizontalAlignment` | `Alignment.Horizontal` | Align children horizontally.                        |

---

## 💡 Example

```kotlin
Column(
    modifier = Modifier.fillMaxSize(),
    verticalArrangement = Arrangement.SpaceEvenly,
    horizontalAlignment = Alignment.CenterHorizontally
) {
    Text("Top")
    Text("Middle")
    Text("Bottom")
}
```

---

## 🖼️ Preview

```kotlin
@Preview
@Composable
fun PreviewColumn() {
    Column {
        Text("Column Item")
    }
}
```

