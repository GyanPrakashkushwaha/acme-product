# acme-product-docs-marp

This project is a presentation created using Marp, a Markdown presentation tool. It includes a custom theme and various features such as pagination, background images, and math rendering.

## Project Structure

- **dist/**: This folder will contain the exported files (HTML, PDF, PPTX, PNGs) after running the build commands.
- **images/**: This folder contains images used in the presentation. It includes `bg-grid.png`, which is the background image for the slides.
- **themes/**: This folder contains custom themes for the presentation. It includes `product-docs.css`, which defines the styles for the custom theme.
- **.gitignore**: This file specifies files and directories that should be ignored by git, including `node_modules/`, `dist/`, and any log files.
- **package.json**: This file is the configuration file for npm. It includes project metadata, dependencies, and scripts for building and exporting the presentation.
- **slides.md**: This file contains the presentation content in Markdown format. It includes Marp directives and various features such as math examples and a background image.

## Setup Instructions

1. **Install Prerequisites**: Ensure you have Node.js LTS installed, which includes npm.
2. **Clone the Repository**: Clone this repository to your local machine.
3. **Install Dependencies**: Navigate to the project folder and run `npm install` to install the necessary dependencies.
4. **Run Live Preview**: Use `npm run start` to start a live preview of the presentation.
5. **Export the Presentation**: Run the following commands to export the presentation in different formats:
   - `npm run build` for HTML
   - `npm run pdf` for PDF
   - `npm run pptx` for PPTX
   - `npm run images` for PNGs

## Custom Theme

The custom theme is defined in `themes/product-docs.css`. You can modify this file to change the appearance of the slides.

## Contributing

Feel free to contribute to this project by submitting issues or pull requests. 

## License

This project is licensed under the MIT License.