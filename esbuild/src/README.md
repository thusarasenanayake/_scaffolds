# Node

> esbuild app.js --bundle --platform=node --target=node10.4

> esbuild app.jsx --bundle --platform=node --packages=external

If you do this, your dependencies must still be present on the file system at run-time since they are no longer included in the bundle.

# Browser

> esbuild app.jsx --bundle --minify --sourcemap --target=chrome58,firefox57,safari11,edge16