# Liquid Glass Compose: A Glassmorphism Library for Jetpack Compose ✨

![GitHub release](https://img.shields.io/github/release/andrea60727/liquid-glass-compose.svg) ![License](https://img.shields.io/badge/license-MIT-blue.svg)

## Overview

Liquid Glass Compose is a powerful library designed for Jetpack Compose, focusing on the trendy glassmorphism design style. This library utilizes AGSL shaders, available for Android 13 and above, to create stunning visual effects. With support for blur, distortion, shadows, and more, you can easily enhance your app's user interface.

### Features

- **Blur Effects**: Add depth to your UI by incorporating soft blur effects.
- **Distortion**: Create unique visual experiences with distortion effects.
- **Shadows**: Enhance your components with realistic shadows.
- **Customizable**: Tailor the effects to fit your app's theme and design.

## Getting Started

To start using Liquid Glass Compose, you need to add the library to your project. Follow these steps:

### Prerequisites

- Android Studio (Arctic Fox or later)
- Jetpack Compose
- Android 13 or higher

### Installation

Add the following dependency to your `build.gradle` file:

```groovy
dependencies {
    implementation 'com.andrea60727:liquid-glass-compose:1.0.0'
}
```

### Usage

Here's a simple example of how to use the Liquid Glass library in your Jetpack Compose application:

```kotlin
import com.andrea60727.liquidglasscompose.*

@Composable
fun GlassCard() {
    GlassCard(
        modifier = Modifier
            .fillMaxWidth()
            .height(200.dp)
            .padding(16.dp),
        blurRadius = 10.dp,
        shadowColor = Color.Black.copy(alpha = 0.3f)
    ) {
        Text("Hello, Glassmorphism!", style = MaterialTheme.typography.h6)
    }
}
```

### Advanced Usage

For more advanced usage, you can customize the properties of the glass effects:

```kotlin
GlassCard(
    modifier = Modifier.fillMaxSize(),
    blurRadius = 15.dp,
    distortionAmount = 5.dp,
    shadowColor = Color.Gray.copy(alpha = 0.5f)
) {
    // Your content here
}
```

## Examples

You can find various examples showcasing the capabilities of Liquid Glass Compose in the `examples` directory of this repository. These examples demonstrate how to implement different effects and styles.

## Documentation

Comprehensive documentation is available in the `docs` folder. You can explore the API, learn about the different components, and find detailed guides on how to implement specific features.

## Release Notes

For the latest updates and changes, please check the [Releases section](https://github.com/andrea60727/liquid-glass-compose/releases). You can download the latest version and execute it in your project.

## Contributing

We welcome contributions to improve Liquid Glass Compose. If you want to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push to your branch.
5. Create a pull request.

### Code of Conduct

Please adhere to the [Code of Conduct](CODE_OF_CONDUCT.md) while contributing to this project.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Support

If you encounter any issues or have questions, please open an issue in the repository. We appreciate your feedback and suggestions.

## Acknowledgments

Thanks to the Jetpack Compose team for their amazing work and to the community for their support. Your contributions make this project better.

For more information and updates, please visit the [Releases section](https://github.com/andrea60727/liquid-glass-compose/releases).