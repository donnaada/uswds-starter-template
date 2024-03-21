# USWDS Starter Template

---

A site created using the [USWDS Tutorial Template](https://github.com/uswds/uswds-tutorial?tab=readme-ov-file) as a starting point.

---

## Requirements

- Node v18
- Git

## Installation

1. Clone repo, either in the terminal or using the `Use this template` button near the top-right of the page and if you have not created a new directory for the project, include that in the `git clone` command.

    ```bash
    git clone https://github.com/donnaada/uswds-starter-template.git <<DIRECTORY_NAME>>
    ```

    `cd` to this new directory:

    ```bash
    cd <<DIRECTORY_NAME>>
    ```

1. Install the project dependencies:

    ```bash
    npm install
    ```
   

1. Initiate Gulp

    ```bash
    npx gulp init
    ```

    Script creates the following new USWDS assets in an `./assets/uswds` directory, theme files in a `./_theme directory`, and compiled CSS in the `./assets/uswds/css` directory.


1. Start the tutorial server:

    ```bash
    npm start
    ```

1. Once the server is running, you can view the site on [http://localhost:8080](http://localhost:8080)

## Custom CSS

Add custom css to `_theme/_uswds-theme-custom-styles.scss`.

## Favicon

Place site favicons in an `./assets/img/site/favicon` directory

## Resources

- [U.S. Web Design Systems](https://designsystem.digital.gov)
- [11ty](https://www.11ty.dev)
- [Liquid](https://shopify.github.io/liquid/)
