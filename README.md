Python 3.10.0 (v3.10.0:b494f5935c, Oct  4 2021, 14:59:19) [Clang 12.0.5 (clang-1205.0.22.11)] on darwin
Type "help", "copyright", "credits" or "license()" for more information.
# Noone Function

This project contains the Noone function, a simple Blockless function for demonstration purposes.

## Function Description

The Noone function is a minimal Blockless function that doesn't perform any specific task. It serves as a template or starting point for building more complex Blockless functions.

## Configuration

### Function Details

- **Name**: Noone
- **Type**: Function
- **Version**: 1.0.0
- **Content Type**: JSON

### Deployment

The function is deployed with the following configuration:

- **Nodes**: 1
- **Permissions**: None

### Build Configuration

The function is built with the following settings:

- **Build Directory**: build
- **Debug Entry Point**: noone_debug.wasm
- **Debug Build Command**: npm run build:debug
- **Release Entry Point**: noone.wasm
- **Release Build Command**: npm run build:release

## Usage

1. Clone the project.
2. Install dependencies by running `npm install`.
3. Build the function in debug mode with `npm run build:debug`.
4. Build the function for release with `npm run build:release`.
5. Deploy the function using the Blockless CLI.
6. Execute the function.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
