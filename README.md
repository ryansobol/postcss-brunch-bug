# postcss-brunch-bug

```
$ env DEBUG='brunch:*' npm run build

> @0.1.0 build /Users/ryansobol/Desktop/postcss-brunch-map-bug
> brunch build

  brunch:config Trying to load brunch-config +0ms
  brunch:plugins Loaded plugins: postcss-brunch +93ms
  brunch:watch add package.json +40ms
  brunch:watch add brunch-config.js +1ms
  brunch:watch add app/styles/index.css +3ms
  brunch:list Reading app/styles/index.css +1ms
  brunch:file Init app/styles/index.css: isntModule=false isWrapped=false +4ms
  brunch:pipeline Compiling app/styles/index.css @ PostCSSCompiler +4ms
  brunch:pipeline Dependencies app/styles/index.css @ PostCSSCompiler +11ms
  brunch:file Generated source map for 'app/styles/index.css'  +2ms
{ Error: ENOENT: no such file or directory, open 'index.css'
  at Error (native)
 errno: -2, code: 'ENOENT', syscall: 'open', path: 'index.css' }
  brunch:list Compiled app/styles/index.css +28ms
  brunch:write Writing 1/1 files +74ms
  brunch:generate Concatenating [app/styles/index.css] => public/app.css +3ms
  brunch:generate Writing public/app.css +2ms
  brunch:generate Writing public/app.css.map +3ms
  brunch:write Writing 0/0 static files, removing 0 +1ms
09 Aug 21:29:45 - info: compiled index.css into app.css in 764ms
```
