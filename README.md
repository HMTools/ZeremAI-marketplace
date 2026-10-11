# ZeremAI-marketplace

Official template library for the [ZeremAI](https://github.com/HMTools/ZeremAI) framework.

## Overview

This repository contains the **core infrastructure** flow templates for the ZeremAI framework. Domain-specific templates (e.g., SDLC workflows) are maintained in separate repositories. Step definitions live as subdirectories within each flow template.

## Structure

```
templates/
  flows/               # Flow templates (full workflow definitions)
    infrastructure/        # Framework/tooling infrastructure workflows
      create-flow-template/
        create-flow-template.json
        plan-and-design-template/   # Step subdirectory
        create-template-file/       # Step subdirectory
        validate-flow-steps-exist/  # Step subdirectory
      ...
```

## Usage

This repository is pre-configured as the `official` marketplace out of the box, so no setup is required:

1. Open the **Marketplace** section in the UI
2. Click **Refresh** to fetch the template catalog
3. Browse and install the templates you need

To add it manually (e.g. under a different name or priority), use **Add Marketplace** in the Marketplace Sources section with URL `https://github.com/HMTools/ZeremAI-marketplace.git`.

### Multi-Marketplace Configuration

The framework supports multiple marketplaces. Each marketplace is refreshed independently. Configure additional marketplaces via the UI Settings or in `~/.claude/zeremai/config/marketplaces.json`.

## Related Repositories

- **[sdlc-flow-templates](https://github.com/HMTools/sdlc-flow-templates)** -- SDLC flow templates (work item implementation, test planning, deployment, PR review, etc.)

## License

See [ZeremAI](https://github.com/HMTools/ZeremAI) for license information.
