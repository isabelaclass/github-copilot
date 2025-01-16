# Credit Card Brand Identifier

This project was developed as part of a GitHub Copilot course challenge, where we collaboratively created (me and IA) a JavaScript function to identify the brand of a credit card based on its number.

## Features

The program identifies the following credit card brands:
- **Visa**: Starts with `4`.
- **Mastercard**: Starts with digits between `51-55` or `2221-2720`.
- **Elo**: Starts with specific prefixes such as `4011`, `4312`, or `4389`.
- **American Express**: Starts with `34` or `37`.
- **Discover**: Starts with `6011`, `65`, or ranges from `644-649`.
- **Hipercard**: Starts with `6062`.

If the input doesn't match any of these patterns, it returns `"Unknown Brand"`.
