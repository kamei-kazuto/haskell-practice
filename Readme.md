# Haskell practice

## Haskell Setup

### install page

https://www.haskell.org/downloads#minimal

### brew install

```
brew install ghc
```

### stack install

stack command make haskell project.

```
curl -sSL https://get.haskellstack.org/ | sh
```

## interpreter

start command

```
ghci
```

exit command

```
:quit
```

## Compile & Execution

add Main.hs file

```haskell
main = do
    print "Hello, World!"
```

compile & execution

```shell
ghc ./helloworld/Main.hs
./helloworld/Main
```

## create webapp

sample-web-app directory is sample project

create project

```
stack new sample-web-app
```

build

```
stack build
```

execution

```
stach exec sample-web-app-exe
```
