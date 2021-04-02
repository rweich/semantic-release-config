# semantic-release-config

default config for my ts-projects

## Installation

1. Install dependencies

    ```shell
    yarn add --dev semantic-release @rweich/semantic-release-config
    ```

1. Configure
    1. either add the config to your `release.config.js`:

        ```javascript
        module.exports = {
          extends: "@rweich/semantic-release-config",
          branches: "main"
        };
        ```

    1. or add it to your `package.json`:

        ```json
        {
          "release": {
            "extends": "@rweich/semantic-release-config",
            "branches": "main"
          }
        }
        ```

1. Usage

   Test with:

   ```shell
   yarn semantic-release --dry-run
   ```
