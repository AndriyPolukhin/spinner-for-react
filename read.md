# Modern Project

### 1) Varsion control

### 2) Automated CI/CD

```
 Build process:
 Automated sequence of tasks that runs on each push, tag and/or release.

 Stages:
 1. install
  - clean install - npm ci
  - security audit - npm audit
 2. lint
  - linter - eslint / stylelint
  - formatter - prettier
    [ Resources: https://editorconfig.org/ ]
    [Plugins: husky, lint-staged]
 3. test
  - test suite - jest / mocha / ava
  - code coverage - nyc / codecov / coveralls
 4. build
  - transpile - babel / typescript / flow
  - pre-process (compile, auto-prefix, etc.) - sass / less / postcss
  - uglify (minify, mingle, optimize, etc) -  uglify-js / terser
  - bundle (concat, tree-shake, etc.) - webpack / rollup / parcel
  - compress (gzip, etc.)
  - other
      - copy / delete / move files
      - check bundle size
      - strip unused code (ts/flow/proptypes)
 5. push
  -  release - github / bitbucket / gitlab
  -  publish - npm / other registry
 6. deploy
  - host - heroku / surge / github-pages / etc

  Task execution
  - CLI (npm)
  - task runner
    - grunt, gulp, brunch
```

### 3. Code quality

### 4. Tooling

### 5. Module support

### 6. Documented API

### 7. Demos
