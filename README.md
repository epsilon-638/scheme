## Write yourself a scheme in 48 hours
#### Currently revisiting https://upload.wikimedia.org/wikipedia/commons/a/aa/Write_Yourself_a_Scheme_in_48_Hours.pdf by Jonathan Tang
```bash
ghc -package parsec -o parser parser.hs
```
### Input
```bash
./parser "(+ 4 5 (* 8 9) (/ 2 4))"
```
### Outpus
`81`
