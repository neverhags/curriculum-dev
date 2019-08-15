# Curriculum Vue Development repo
---

### Run: 
        $ npm install
        $ npm run dev
        $ npm run prod
        
### package.json scripts:
        
          "scripts": {
            "test:unit": "jest --config test/jest.config.js",
            "test": "npm run lint && npm run test:unit",
            "test:debug": "node --inspect node_modules/.bin/jest --runInBand --config test/jest.config.js",
            "dev": "webpack-dev-server --progress --config build/webpack.config.dev.js",
            "prod": "webpack --config build/webpack.config.prod.js",
            "eslint": "eslint --ext .js,.vue src",
            "eslint:fix": "eslint --ext .js,.vue src --fix"
          },
          
          
#### Tengo sueño no me juzguen... mañana sigo...