# keyd.conf
# /etc/keyd/default.conf config for capslock remap
```yaml

[ids]

*

[main]

capslock = overload(custom, esc)

# ctrl_vim modifier layer; inherits from 'Ctrl' modifier layer

[custom:C]

s = left
d = down
e = up
f = right
# forward word
g = C-right
# backward word
a = C-left
c = C-S-left
v = C-S-right
r = enter
w = backspace
q = esc
j = (
k = )
u = {
i = }
m = [
, = ]
```
