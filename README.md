# immich-cli snap

Unofficial snap packaging of the [Immich CLI](https://immich.app/docs/features/command-line-interface) (`@immich/cli` v3.2.0) — a command-line tool for uploading photos and videos to an Immich server.

## Install

```bash
sudo snap install immich-cli
```

## Usage

```bash
immich --help
immich upload --help
```

For full documentation, see the [Immich CLI docs](https://immich.app/docs/features/command-line-interface).

## Build

Prerequisites: [Snapcraft](https://snapcraft.io/snapcraft) and LXD (for building in a clean environment).

```bash
snapcraft
```

This bundles Node.js 22 and the Immich CLI into a strictly-confined snap on `core24`.

## License

AGPL-3.0