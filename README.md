## Prerequisites

`docker run -it -v /root/:/root/ -v /home/qgb/:/home/qgb/ -v /home/qgb/node/usr_local:/usr/local/  -w "/home/qgb/qgv" -p 3000:3000 -p 9000:9000 node bash`

### In Docker:
`/home/qgb/qgv# ./tmux has||./tmux new -Ad;./ttyd -p 3000 bash -c '/home/qgb/qgv/tmux at'`

`cd repo_path`

`yarn` or `yarn install`

## Development

1. modify `webpack.config.js > devConfig > proxy > target` the ws server
2. Start the dev server: `yarn run start`

## Publish

Run `yarn run build`, this will compile the inlined html to `../src/html.h`
