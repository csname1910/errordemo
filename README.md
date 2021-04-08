# Reproduce error:

Type:

git clone https://github.com/csname1910/errordemo

cd errordemo

npm install

npm start

# You will get this error:

Error: ./node_modules/pdfjs-dist/build/pdf.js 2413:45
Module parse failed: Unexpected token (2413:45)
File was processed with these loaders:
 * ./node_modules/@angular-devkit/build-angular/src/babel/webpack-loader.js
 * ./node_modules/@ngtools/webpack/src/ivy/index.js
You may need an additional loader to handle the result of these loaders.
|         intent: renderingIntent,
|         renderInteractiveForms: renderInteractiveForms === true,
>         annotationStorage: annotationStorage?.getAll() || null
|       });
|     }

# Why?
