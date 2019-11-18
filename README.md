# VSCode React Component Generator for TypeScript

(**ts-react-generator**)

[![Version](https://vsmarketplacebadge.apphb.com/version/wiedymi.ts-react-generator.svg)](https://marketplace.visualstudio.com/items?itemName=wiedymi.ts-react-generator)
[![Installs](https://vsmarketplacebadge.apphb.com/installs/wiedymi.ts-react-generator.svg)](https://marketplace.visualstudio.com/items?itemName=wiedymi.ts-react-generator)
[![GitHub](https://flat.badgen.net/github/release/wiedymi/ts-react-generator)](https://github.com/wiedymi/ts-react-generator/releases)

## Description

The extension automatically creates folder for react component containing:

- `index.ts`
- `component.tsx`
- `styles.ts` (for `styled`-component or `emotion` option)
- `container.ts` (for Redux)

## Installation

Install through VS Code extensions. Search for `VSCode React Component Generator for TypeScript`

[Visual Studio Code Market Place: VSCode React Component Generator](https://marketplace.visualstudio.com/items?itemName=wiedymi.ts-react-generator)

Can also be installed in VS Code: Launch VS Code Quick Open (Ctrl+P), paste the following command, and press enter.

```bash
ext install wiedymi.ts-react-generator
```

## Usage

- Right click on the file or folder in the file explorer
- Select one of following options:
  - "New Class component"
  - "New Class component with Redux"
  - "New Functional component"
  - "New Functional component with Redux"
- Enter a component name in the pop up in camelCase or PascalCase. If you enter the component name as in camelCase, then extension will convert it PascalCase automatically.
