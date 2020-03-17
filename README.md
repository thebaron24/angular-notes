# angular-notes
Useful notes for developing with Angular


## CLI

npx -p @angular/cli ng new angular-universal

cd angular-universal

npx -p @angular/cli ng add @nguniversal/express-engine

npx -p @angular/cli ng add @angular/material

npx -p @angular/cli ng g service data


## Server Side Rendering without repeat api calls on client
ADD TransferHttpCacheModule to prevent duplicate get calls when transferring to client side
https://github.com/angular/universal/blob/master/docs/transfer-http.md

https://stackoverflow.com/questions/8461528/replace-github-repo-while-preserving-issues-wiki-etc
