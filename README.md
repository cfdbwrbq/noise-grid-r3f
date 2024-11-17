# r3f-template
A basic template for R3F projects

```
yarn
yarn dev
```

![image](./public/screenshot.jpg)


```
npm install
npx webpack --config webpack.config.js --mode production
cd dist
python3 -m http.server
http://localhost:8000/
optional: remove `<script type="module" src="/src/main.jsx"></script>` from dist/index.html body
```