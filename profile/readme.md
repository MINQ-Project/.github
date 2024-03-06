# MINQ
MINQ (MINQ Integrated Query) is a special programming language inspired by C#, Python and Javascript.
## Getting started
> [!WARNING]
> Binaries aren't published yet.
> I will add them later.
________________
When You Have MINQ on your computer you can try to run Interactive Mode (Console Mode) using `minq` command.
Try to run this simple Hello World program (write it line-by-line):
```ts
import console
console.write("Hello, world!\n")
```
### First MINQ Script
Then you can make a file with .mq (or .minq) extension and type Hello World program from before. Save it and run it using `minq` command:
```bat
minq -f <name>.mq
```

## Using MPS
Try to run your program using `MPS` (MINQ Package System):
```
mps init
```
this will create a pkg.json file for your project. you can type values manually or use -y flag (yes) to make a template pkg.json.
> [!NOTE]
> If you used -y flag you must change the main filename in pkg.json or rename your script to `index.mq`
to run a mps package type:
```
mps
```
it will run the package
# Congratulations, you runned your first MINQ program!!! (-:
