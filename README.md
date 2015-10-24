# Requirements

- node (``~4.2``)
- npm (``~3.3``)
- TypeScript (``~1.6``)

# Run the app

```
npm install # Install dependencies
npm run tsc # Compile the TypeScript to JavaScript
npm start # Run the app
```

# Troubleshooting

## reactivex is not in the npm registry

Update npm:

```
sudo npm cache clean -f
sudo npm install -g n
sudo n stable
```
