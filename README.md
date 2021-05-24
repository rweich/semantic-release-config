# semantic-release-config
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Frweich%2Fsemantic-release-config.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Frweich%2Fsemantic-release-config?ref=badge_shield)


Default config for my ts-projects. foo more

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


## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Frweich%2Fsemantic-release-config.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Frweich%2Fsemantic-release-config?ref=badge_large)