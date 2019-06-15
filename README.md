# pgo


[![CircleCI](https://circleci.com/gh/yourgithubhandle/pgo/tree/master.svg?style=svg)](https://circleci.com/gh/yourgithubhandle/pgo/tree/master)


**Contains the following libraries and executables:**

```
pgo@0.0.0
│
├─test/
│   name:    TestPgo.exe
│   main:    TestPgo
│   require: pgo.lib
│
├─library/
│   library name: pgo.lib
│   namespace:    Pgo
│   require:
│
└─executable/
    name:    PgoApp.exe
    main:    PgoApp
    require: pgo.lib
```

## Developing:

```
npm install -g esy
git clone <this-repo>
esy install
esy build
```

## Running Binary:

After building the project, you can run the main binary that is produced.

```
esy x PgoApp.exe 
```

## Running Tests:

```
# Runs the "test" command in `package.json`.
esy test
```
