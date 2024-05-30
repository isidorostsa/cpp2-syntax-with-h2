## Forked Cpp2 syntax highlighting
The only purpose of this fork is to add `.h2` files to the list of the affected file extensions.

## Build

To install run the following from the root of this project, using yarn classic (later versions do not use the `list` command that this project relies on). After that a `.vsix` file will be created in the cpp2 directory. Click on the "..." in the extensions tab and select install from VSIX and pick this file to install it locally.
```bash
yarn install
yarn run build
yarn run package
```

The output VSIX file is located under `cpp2`.
