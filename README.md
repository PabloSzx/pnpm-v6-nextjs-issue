# Next.js with PNPM v6 issue

```sh
pnpm i
pnpm dev
```


```
λ pnpm dev

> nextjs-pnpm-v6@1.0.0 dev C:\Users\pablo\nextjs-pnpm-v6
> next

ready - started server on 0.0.0.0:3000, url: http://localhost:3000
info  - Using webpack 5. Reason: future.webpack5 option enabled https://nextjs.org/docs/messages/webpack5
internal/fs/utils.js:628
    throw err;
    ^

TypeError [ERR_INVALID_ARG_VALUE]: The argument 'path' must be a string or Uint8Array without null bytes. Received 'C:\\Users\\pablo\\nextjs-pnpm-v6\\node_modules\\.pnpm\\@next\x00#react-refresh-utils@10.1.3_react-refresh@0.8.3\\node_modules\\...
    at Object.realpath (fs.js:1800:3)
    at C:\Users\pablo\nextjs-pnpm-v6\node_modules\.pnpm\next@10.1.3_19437c2f9b137c4ee9c416360487a7aa\node_modules\next\dist\compiled\webpack\bundle5.js:50288:15
    at processQueue (C:\Users\pablo\nextjs-pnpm-v6\node_modules\.pnpm\next@10.1.3_19437c2f9b137c4ee9c416360487a7aa\node_modules\next\dist\compiled\webpack\bundle5.js:129193:4)
    at processTicksAndRejections (internal/process/task_queues.js:75:11) {
  code: 'ERR_INVALID_ARG_VALUE'
}
 ERROR  Command failed with exit code 1.
```