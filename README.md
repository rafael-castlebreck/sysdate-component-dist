# SysDate Component #

Production version of [system date component](https://github.com/rafael-castlebreck/sysdate-component-dev).

## Installation ##

You can use npm fetch the package from or, alternatively, manually the component url in package.json

I) Directly from Repository:

```
npm install "git+https://github.com/rafael-castlebreck/sysdate-component-dist.git"
```

II) Manually added in package.json

```
  "dependencies": {
    ...
    "sysdate-component": "git+https://github.com/rafael-castlebreck/sysdate-component-dist.git"
  },
```

## Usage ##

A simple example will be enough to grab the idea.

```
import  SysDate  from 'sysdate-component';

function App() {
  return (
    <div className="App">
      <header className="App-header">
        <SysDate/>
      </header>
    </div>
  );
}

```
