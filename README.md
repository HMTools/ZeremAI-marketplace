<p align="center"><img src="assets/hero.webp" alt="ZeremAI Marketplace: the flows and templates hub for Claude Code" width="100%"></p>

# ZeremAI-marketplace

Official template library for the [ZeremAI](https://github.com/HMTools/ZeremAI) Claude Code plugin.

## 📖 Documentation

**https://zerem-ai.mintlify.app**

- [Marketplaces: install and manage templates](https://zerem-ai.mintlify.app/guide/marketplaces)
- [Write a template](https://zerem-ai.mintlify.app/authoring/templates) and [write a step](https://zerem-ai.mintlify.app/authoring/steps)

This repo holds the templates only.

## Templates

Core infrastructure flows in `templates/flows/infrastructure/`:

`create-flow-template` · `update-flow-template`

Domain templates live elsewhere, for example [sdlc-flow-templates](https://github.com/HMTools/sdlc-flow-templates).

## Use

This repo is the `official` marketplace in ZeremAI by default. Run `/zeremai`, open **Templates**, **Refresh**, then **Install**.

To add it under another name: URL `https://github.com/HMTools/ZeremAI-marketplace.git`.

## Contributing

Fork, add or change a template under `templates/flows/{category}/{template}/` (steps are subfolders), open a pull request. Format: see [Write a template](https://zerem-ai.mintlify.app/authoring/templates).

## License

[MIT](LICENSE). Contributions use the same license, see [CONTRIBUTING](CONTRIBUTING.md).
