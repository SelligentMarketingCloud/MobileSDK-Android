//[sdk](../../index.md)/[com.selligent.sdk](index.md)/[SMDialog](-s-m-dialog.md)

# SMDialog

[androidJvm]\

@[Composable](https://developer.android.com/reference/kotlin/androidx/compose/runtime/Composable.html)

fun [SMDialog](-s-m-dialog.md)(modifier: [Modifier](https://developer.android.com/reference/kotlin/androidx/compose/ui/Modifier.html) = Modifier, shape: [Shape](https://developer.android.com/reference/kotlin/androidx/compose/ui/graphics/Shape.html) = ShapeDefaults.ExtraLarge, containerColor: [Color](https://developer.android.com/reference/kotlin/androidx/compose/ui/graphics/Color.html) = MaterialTheme.colorScheme.surface, titleContentColor: [Color](https://developer.android.com/reference/kotlin/androidx/compose/ui/graphics/Color.html) = MaterialTheme.colorScheme.onSurface, textContentColor: [Color](https://developer.android.com/reference/kotlin/androidx/compose/ui/graphics/Color.html) = MaterialTheme.colorScheme.onSurfaceVariant, buttonContentColor: [Color](https://developer.android.com/reference/kotlin/androidx/compose/ui/graphics/Color.html) = MaterialTheme.colorScheme.primary, buttonContainerColor: [Color](https://developer.android.com/reference/kotlin/androidx/compose/ui/graphics/Color.html) = MaterialTheme.colorScheme.surface, buttonShape: [Shape](https://developer.android.com/reference/kotlin/androidx/compose/ui/graphics/Shape.html) = ShapeDefaults.Medium, tonalElevation: [Dp](https://developer.android.com/reference/kotlin/androidx/compose/ui/unit/Dp.html) = DialogDefaultTonalElevation, properties: [DialogProperties](https://developer.android.com/reference/kotlin/androidx/compose/ui/window/DialogProperties.html) = DialogProperties())

This will display the dialog type in-app message in your jetpack compose activity extending ComponentActivity

#### Parameters

androidJvm

| | |
|---|---|
| modifier | the [Modifier](https://developer.android.com/reference/kotlin/androidx/compose/ui/Modifier.html) to be applied to this dialog |
| shape | defines the shape of this dialog's container |
| containerColor | the color used for the background of this dialog. |
| titleContentColor | the content color used for the title. |
| buttonContentColor | the content color used for the buttons. |
| buttonContainerColor | the content color used for the background of the buttons. |
| buttonShape | defines the shape of the dialog's buttons |
| tonalElevation | when [containerColor](-s-m-dialog.md) is [ColorScheme.surface](https://developer.android.com/reference/kotlin/androidx/compose/material3/ColorScheme.html#surface), a translucent primary color overlay is applied on top of the container. A higher tonal elevation value will result in a darker color in light theme and lighter color in dark theme. See also: [Surface](https://developer.android.com/reference/kotlin/androidx/compose/material3/package-summary.html). |
| properties | typically platform specific properties to further configure the dialog. |
