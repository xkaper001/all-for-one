# try Changelog

## [0.1.0] - 2025-12-15

- Initial release of **One for All** extension.
- Added **Base Converter** command (`base`):
    - Support for Decimal, Hexadecimal, Binary, Octal, ASCII.
    - Support for Codecs: Base64, Base58, URL Encoding, HTML Entities.
    - Recursive conversion support (e.g. `text | 5` for 5 rounds).
- Added **Hash** command (`hash`):
    - Support for MD5, SHA1, SHA256, SHA512.
    - Recursive hashing support.
- Added **Decrypt Vigenere** command (`decrypt-vigenere`):
    - Decrypt Vigenère ciphers with a key.
    - Support for Form-based input.
- Added **Clipboard Auto-fill**:
    - Automatically populates input from clipboard for all commands.
- Added **Caesar Cipher** command (`decrypt-caesar`):
    - Decrypt with Shift N.
    - Support for 5 alphabet types (English, Digits, Latin, ASCII, Custom).