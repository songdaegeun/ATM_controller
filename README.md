
## environment
[os] macos 13.3
[g++ version] arm64-apple-darwin22.4.0

## complile
g++ -std=c++17 atm_controller.cpp -o atm_controller

## execute
./atm_controller

## test case
script1
```
zzz
n
```
script2
```
y
1234
1
2
4000000000
y
2
4000000000
n
y
1
y
2
10
y
1
n
n

```
script3
```
y
aaa
1111
1234
aaa
1111
1
y
2
333
y
1
y
3
500
y
1
y
3
33
y
1
zzz
2
1
y
2
1234
zzz
1
1
zzz
2
1
zzz
n
```