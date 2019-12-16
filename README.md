# Hugo Radio

This is a hugo theme for podcast usecases.

## Configuration

```toml
baseURL = "https://example.com/"
languageCode = "en-us"
title = "Example Radio"
theme = "radio"
googleAnalytics = "UA-12345-1"

[menu]
    [[menu.main]]
        identifier = "who"
        name = "Who are we?"
        weight = 10
    [[menu.main]]
        parent = "who"
        identifier = "about"
        name = "About us"
        url = "/about"
        weight = 10
    [[menu.main]]
        parent = "who"
        identifier = "contact"
        name = "Contact us"
        url = "/contact"
        weight = 20

[params]
    langDir = "ltr"
    author = "Mehdy Khoshnoody"
    contact = "info@example.com"
    logo = "logo.png" # Place the `logo.png` file in `static` directory
```
