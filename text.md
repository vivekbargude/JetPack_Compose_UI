Great! Here are the markdown files for the following Jetpack Compose UI components: `Text`, `Row`, `Column`, `Card`, and `Box`. You can save each file under a `/components` folder in your GitHub repository.

---

### 📄 `Text.md`

````md
# 📝 Text Component

The `Text` composable is used to display text in the UI.

---

## 🛠️ Usage

```kotlin
Text(text = "Hello, Jetpack Compose!")
````

---

## 📌 Parameters

| Parameter    | Type           | Description                                      |
| ------------ | -------------- | ------------------------------------------------ |
| `text`       | `String`       | The string to display.                           |
| `modifier`   | `Modifier`     | Modifier to apply layout or style changes.       |
| `color`      | `Color`        | Text color.                                      |
| `fontSize`   | `TextUnit`     | Text size like `16.sp`.                          |
| `fontWeight` | `FontWeight`   | Bold, Light, Normal etc.                         |
| `fontStyle`  | `FontStyle`    | Italic or Normal.                                |
| `textAlign`  | `TextAlign`    | Alignment of text (Start, Center, End, Justify). |
| `maxLines`   | `Int`          | Maximum number of lines.                         |
| `overflow`   | `TextOverflow` | How to handle overflow (clip, ellipsis, etc.).   |

---

## 💡 Example

```kotlin
Text(
    text = "Welcome to Compose!",
    fontSize = 20.sp,
    color = Color.Magenta,
    fontWeight = FontWeight.Bold,
    textAlign = TextAlign.Center
)
```

---

## 🖼️ Preview

```kotlin
@Preview
@Composable
fun PreviewText() {
    Text(text = "Hello Preview!")
}
```

````



