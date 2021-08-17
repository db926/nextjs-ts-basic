my-ts-app

==============================================================================================================================
Requirements
==============================================================================================================================

Required VScode extensions for DEVELOPERS

1. ESlint - https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint
2. Prettier - https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode

--> Yarn Package manager must be Installed globally

==============================================================================================================================
After Cloing the Repo
==============================================================================================================================

run 'yarn husky install' to enable husky

' yarn husky add .husky/pre-commit "yarn tsc --noEmit && yarn eslint --fix . && yarn prettier --write ." '

Note: If you want to skip the check, you can add a --no-verify flag to your commit command. For example: git commit --no-verify -m "Update README.md"

Essential Commands :-

yarn tsc --noEmit <!-- Type check TypeScript files -->
yarn eslint --fix . <!-- Type check TypeScript files -->
yarn prettier --write
