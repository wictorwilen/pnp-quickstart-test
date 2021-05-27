FROM mcr.microsoft.com/vscode/devcontainers/javascript-node:0-14

RUN adduser --system pnp
USER pnp

RUN  bash -c 'npm install gulp-cli yo generator-teams @pnp/cli-microsoft365 --global --production --quiet --no-progress' 
