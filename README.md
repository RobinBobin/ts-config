# Installation

Install the following packages:

    pnpm i --save-dev @robinbobin/ts-config typescript@^5.9.3

# Config files

## tsconfig.json

A script invoked during `postinstall` copies a sample TS config, named `tsconfig.json_<number>` to your project root dir. You can copy this file manually if you don't want to let `postinstall` execute:

    cp node_modules/@robinbobin/ts-config/tsconfig.json_<number> .
