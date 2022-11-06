https://khalidabuhakmeh.com/install-tailwind-css-with-aspnet-core

# init node js
npm init -y

```
module.exports = {
  content: [
    '!**/{bin,obj,node_modules}/**',
    '**/*.{html,cshtml}',
  ],
  theme: {
    extend: {},
  },
  corePlugins: {
    preflight: false,
  },
  plugins: [],
}
```