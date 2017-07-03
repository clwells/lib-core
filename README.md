
# NocWorx Core Library

This is the core PHP library for NocWorx.  This library encompasses the most basic core modules used by NocWorx.

## Requirements

All dependencies are laid out in the composer.json file.

## Other Notes

- **DO NOT** use mt_rand() (or any other randomization functions in PHP).  Use the function in `\NocWorx\Lib\Random`.

- **DO NOT** use any crypto except that provided by `\NocWorx\Lib\Crypto`.

- **DO NOT** generate passwords unless using the functions provided by `\NocWorx\Lib\Password`.

- **DO NOT** use `strlen()` directly.  Use the `\NocWorx\Lib\Str::strlen()` variant.

- **DO NOT** use `exec()` directly.  Use the `\NocWorx\Lib\Process::exec()` variant.

- **DO NOT** use `***env()` directly.  Use the `\NocWorx\Lib\Env::xxx()` variant.

- **DO NOT** use any `hash***()` functions directly.  Use `\NocWorx\Lib\Hash`.

- **DO NOT** use `json_***()` functions directly.  Use `\NocWorx\Lib\Json`.

## License

MIT
