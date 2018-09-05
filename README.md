# Blueasy template

    "dev": "webpack-dev-server --mode development --open",
    "prod": "rimraf dist && webpack --mode production",
    "lint": "npm run lint:js && npm run lint:css",
    "lint:js": "eslint src/**/*.js",
    "lint:css": "stylelint src/**/*.scss",
    "server:prod": "http-server dist -o"

Didnt work Media Queries in section "contact"

wrong path to background-image from css(dev and prod)
