# Strata Examples

Example applications demonstrating [@jbcom/strata](https://github.com/jbcom/nodejs-strata) - procedural 3D graphics for React Three Fiber.

## Examples

| Example | Description |
|---------|-------------|
| [basic-terrain](./basic-terrain) | Simple terrain generation with height maps |
| [water-scene](./water-scene) | Water effects with waves and caustics |
| [sky-volumetrics](./sky-volumetrics) | Procedural sky with volumetric clouds |
| [vegetation-showcase](./vegetation-showcase) | Instanced vegetation with wind animation |
| [api-showcase](./api-showcase) | Comprehensive API demonstration |

## Quick Start

```bash
# Clone this repository
git clone https://github.com/jbcom/nodejs-strata-examples.git
cd nodejs-strata-examples

# Install dependencies for an example
cd basic-terrain
pnpm install

# Run the development server
pnpm dev
```

## Requirements

- Node.js >= 20
- pnpm (recommended) or npm

## Dependencies

All examples use the published npm package:

```json
{
  "dependencies": {
    "@jbcom/strata": "^1.4.0"
  }
}
```

## Related

- [@jbcom/strata](https://github.com/jbcom/nodejs-strata) - Main library
- [@jbcom/strata-capacitor-plugin](https://github.com/jbcom/nodejs-strata-capacitor-plugin) - Mobile support (Capacitor)
- [@jbcom/strata-react-native-plugin](https://github.com/jbcom/nodejs-strata-react-native-plugin) - Mobile support (React Native)

## License

MIT
