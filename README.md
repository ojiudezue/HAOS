# Home Assistant Automations Repository

A version-controlled collection of my Home Assistant automations, blueprints, and dashboards.

## Overview

This repository contains all of my custom Home Assistant configurations, allowing for proper version control, backup, and sharing. By storing these configurations in Git, I can easily track changes, revert to previous versions if needed, and share my setups with the community.

## Contents

- **Automations**: Custom automations to enhance my smart home experience
- **Blueprints**: Reusable automation templates
- **Dashboards**: Custom Lovelace UI dashboards

## Structure

```
├── automations/
│   ├── lighting/
│   ├── climate/
│   ├── security/
│   └── ...
├── blueprints/
│   ├── motion_lighting.yaml
│   ├── presence_detection.yaml
│   └── ...
└── dashboards/
    ├── main.yaml
    ├── mobile.yaml
    └── ...
```

## Installation

To use these configurations in your own Home Assistant instance:

1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/home-assistant-config.git
   ```

2. Copy the desired configurations to your Home Assistant configuration directory.

3. Restart Home Assistant to apply changes.

## Usage

### Automations

Automations can be imported directly from the `automations/` directory. Each automation is stored as a separate YAML file for easy management.

### Blueprints

To use a blueprint:

1. Go to Home Assistant → Configuration → Blueprints
2. Click "Import Blueprint"
3. Enter the raw GitHub URL for the blueprint (e.g., `https://github.com/YOUR_USERNAME/home-assistant-config/raw/main/blueprints/motion_lighting.yaml`)

### Dashboards

Dashboards can be imported through the Lovelace UI:

1. Go to Home Assistant → Configuration → Lovelace Dashboards
2. Click "Add Dashboard"
3. Select "Import from YAML" and copy the contents of the desired dashboard file

## Contributing

Feel free to submit issues or pull requests if you have suggestions for improvements or have found bugs.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Home Assistant community for inspiration and support
- All the open source contributors who make smart home automation accessible
