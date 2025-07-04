# 🎁 Box Component

`Box` is a layout that stacks its children on top of each other. It's useful when you want to overlay elements.

---

## 🛠️ Usage

    Box {
        Text("Bottom")
        Text("Top")
    }

---

## 📌 Parameters

| Parameter                 | Type        | Description                                        |
|---------------------------|-------------|----------------------------------------------------|
| `modifier`                | `Modifier`  | Apply size, alignment, padding, etc.               |
| `contentAlignment`        | `Alignment` | Align all children inside the box.                 |
| `propagateMinConstraints` | `Boolean`   | Pass min constraints to children (default: false). |

---

## 💡 Example

    Box(
        modifier = Modifier
            .size(100.dp)
            .background(Color.Gray),
        contentAlignment = Alignment.Center
    ) {
        Text("Centered Text", color = Color.White)
    }

---

## 🖼️ Preview

    @Preview
    @Composable
    fun PreviewBox() {
        Box(Modifier.size(120.dp)) {
            Text("Boxed!")
        }
    }

---
