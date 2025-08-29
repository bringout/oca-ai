# OCA Ai

This repository contains **4** OCA packages for ai.

## Packages Included (4 packages)

- **odoo-bringout-oca-ai-ai_oca_bridge** - From ai: ai_oca_bridge
- **odoo-bringout-oca-ai-ai_oca_bridge_chatter** - From ai: ai_oca_bridge_chatter
- **odoo-bringout-oca-ai-ai_oca_bridge_document_page** - From ai: ai_oca_bridge_document_page
- **odoo-bringout-oca-ai-ai_oca_bridge_helpdesk_mgmt** - From ai: ai_oca_bridge_helpdesk_mgmt


## Installation

Install any package from this category:

```bash
# Install from local directory
pip install packages/oca-ai/PACKAGE_NAME/

# Install in development mode  
pip install -e packages/oca-ai/PACKAGE_NAME/

# Using uv (recommended for speed)
uv add packages/oca-ai/PACKAGE_NAME/
```

## Repository Structure

Each package in this repository follows the standard Odoo addon structure:

```
oca-ai/
├── odoo-bringout-oca-PROJECT-ADDON/
│   ├── ADDON_NAME/           # Complete addon code
│   │   ├── __init__.py
│   │   ├── __manifest__.py
│   │   └── ... (models, views, etc.)
│   ├── pyproject.toml        # Python package configuration
│   └── README.md            # Package documentation
└── ...
```

## Contributing

These packages are maintained as part of the [OCA (Odoo Community Association)](https://github.com/OCA) ecosystem.

## License

Each package maintains its original license as specified in the OCA repositories.
