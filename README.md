# ApiForge - GitHub Pages Deployment

This repository hosts the deployed web build of **ApiForge**, a Flutter-based application for loading, parsing, and displaying OpenAPI specifications. The app is live at [https://BalaSubramaniam12007.github.io](https://BalaSubramaniam12007.github.io).

## About ApiForge

ApiForge allows users to:
- Load OpenAPI specs from a URL or local file (JSON/YAML).
- View API endpoints with their methods, paths, and descriptions.
- Filter endpoints using a search bar.
- Export specs as Postman collections for easy testing.

## Live Demo

Visit the deployed app here: [https://BalaSubramaniam12007.github.io](https://BalaSubramaniam12007.github.io)

### Usage
1. On the home screen, enter a URL to an OpenAPI spec (e.g., `https://petstore.swagger.io/v2/swagger.json`) or upload a local `.json`/`.yaml` file.
2. View the API specification, filter endpoints, and export the spec as a Postman collection.

## Source Code

The source code for ApiForge is maintained in a separate repository: [BalaSubramaniam12007/apiforge_v0](https://github.com/BalaSubramaniam12007/apiforge_v0). Visit the `apiforge_v0` repository for the full project details, including:
- Source code and project structure.
- Instructions for running the app locally.
- Contribution guidelines.

## Deployment

This repository is automatically updated by a GitHub Actions workflow defined in the `apiforge_v0` repository. Whenever changes are pushed to the `main` branch of `apiforge_v0`, the workflow:
1. Builds the Flutter web app (`flutter build web --release`).
2. Deploys the build output (from `build/web`) to this repository (`BalaSubramaniam12007.github.io`).
3. Updates the live site on GitHub Pages.

For more details on the deployment process, see the [workflow file](https://github.com/BalaSubramaniam12007/apiforge_v0/blob/main/.github/workflows/deploy.yml) in the `apiforge_v0` repository.

## Contributing

To contribute to ApiForge, please visit the [source repository](https://github.com/BalaSubramaniam12007/apiforge_v0).

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/BalaSubramaniam12007/apiforge_v0/blob/main/LICENSE) file in the `apiforge_v0` repository for details.
