# ChatTriggers Async Await Demo

This repo is just a quick demo of one way to transpile async await code to work in ChatTriggers.

A few things to note. If you publish a module that is transpiled remember to include the source code and tsconfig, but do remove node_modules.

## Issues

Type definitions for the Promise Polyfill might not line up exactly with what typescript thinks is being used. So if you are using some less common method of Promises and it doesn't work contact me and I'll update the module.
