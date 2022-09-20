Create new TS project : > npx create-next-app@latest --ts .    


For Husky Setup
===============================================

# Install Husky v6
npm install husky --save-dev
# or
yarn add husky --dev

# Activate hooks
npx husky install
# or
yarn husky install

npx husky add .husky/commit-msg  "npx --no -- commitlint --edit ${1}"


For CommitLint Setup
====================================================
npm install --save-dev @commitlint/config-conventional @commitlint/cli
Copy .commitlitnrc
Reference URL: https://commitlint.js.org/#/./guides-local-setup?id=guides-local-setup





For Github Action
======================================================
Copy .github folder for workflows


Few steps to do:

yarn add lint-staged --save-dev