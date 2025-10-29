# Installation

Install the following packages:

    pnpm i --save-dev @robinbobin/ts-config typescript@^5.9.3

# Config files

## tsconfig.json

The script invoked during `postinstall` copies a sample TS config to your project root dir, naming the file `tsconfig.json_<number>`. Don't forget to delete the `_<number>` part from the file name. You can copy this sample config manually if you don't want to let `postinstall` execute:

    cp node_modules/@robinbobin/ts-config/tsconfig.json_ ./tsconfig.json
