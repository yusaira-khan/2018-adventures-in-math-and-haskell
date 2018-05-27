# Stack  BooBoo
```bash
$ https://github.com/yusaira-khan/haskell30daysofcode.git
cd haskell30daysofcode
stack new haskell30daysofcode
cd haskell30daysofcode
stack setup
cd ../
mv haskell30daysofcode/* ./
mv *hs src/
stack build
```
the last onre kept complaining it couldn't find Distribution.Simple. Turns out the last mv command was copying a Setup.Hs file to the src/ directory with borked everything. 
