This is a bonus for geek programmers.

[日本語での解説はこちら](https://mametter.hatenablog.com/entry/2021/08/13/092312)

## Decomposition of "nankai.rb"

The word ["難解"](https://jisho.org/word/%E9%9B%A3%E8%A7%A3) has two Kanji letters, ["難"](https://jisho.org/search/%E9%9B%A3%20%23kanji) and ["解"](https://jisho.org/search/%E8%A7%A3%20%23kanji).
Similarly, the program "nankai.rb" can be *vertically* split into the two letters, "nan.rb" and "kai.rb".

### nan.rb

This is the left part of the original program, called "nan.rb".

```
     q=%q!s     =q[/#{          N=?\n}(    #{Z=?\~    
     s}*)/,     1];E=3          3.chr;     $><<t=~    
(N*12+s+"q=%q#{E+q+E};eval#    {Z*8}n=    '#{n}'~     
"+N*13+?#).gsub(/^.*/){(Z*(   35-s.si    ze)+$&)      
     |c|d=d     *90+(c       -2)%91};d};b=116;c=0;i=D 
     `?oT`r     #?jn%:      _(7AF5]7lZ}|N,),slN15Ap8< 
  ]];g=[];F=->x,m{g<<[t[x  ],b>0?[0]*c+[x]*b+m:[0]*(c 
  map{|i|i+=x;s<=i&&i<s+n -170&&(i-s    )%W<n%W       
  <<x;v   <1&&v=D   ["axC4?ap'5.bbU     lui?h|b       
  ".split(??)[(x%W+x/W)%8]];(d+=1;v/=2)while+v%2>0;z= 
  x+=d%8>3?z:-z;v/=2)whil   e-x%W>1&&0<x&&x<8208;F[y, 
          8-'#'L>            *B(B[(*-$XG|"E"H=$H:)$'$ 
  ,n=a;v=B.pop-34;v%3<2?(    z=n%W;     S[s+y=(       
  ;y)]):(b+=200/r+=2;M[D[    "=,)_q     >Z"]>>r       
  170]*19;b=0;T=(c+(0..8)    .map{Z*51+(0..67).map{i/ 
          %w{puts            (["Usage:",:ruby,$0,100] 
/q/)?$q[/^#{z}+/]+z+z+"R=ev  al#{z*18}$q=#{z*35}%q{#$ 
1]:[]};n+z+?=+z+(m>1?f[2]:[  m])*(z     +?x+z))       
        ,n=0,m;6.ti          mes{|i     |c+=10;       
      [i]*684];b=52;t=       T;M[6,(x-i%2)%W+4788]};s=
   {|i|o=[Z*   170]*48*N;    g.map{|c,m|x=m[i]||0;x>0&
ub(N,"\e[E        ");slee    p(0.01)};puts(s)#Unravel#
  "q!;p              0/      0.0;#";                  
```

This is executable as a Ruby program. When executed, it prints "NaN".

```
$ ruby nan.rb
NaN
```

### kai.rb

This is the right part, called "kai.rb".

```
       p="><"
      puts""+              p||$><<"____\n\s/\s/\n";(
      "\u89D2";;x=(%~      );%#?_Y}_U1jojD(i0(DVA1aq
     .ljust(170)};D=->          e{d=0;e.      bytes{
    ["cGIY&    ?dUptZ            yGj5?=       1+wD5G
  XzIUF<+     <L-MlD            )"+t[2        513,21
 -m.size)+m.reverse];t[x]=    Z;[1,-1        ,-W,W].
&&t[i]>Z&&F[i,[i]+m]}};M=- >d,x{y=x;    m=[];v=0;(m
  *?_jJc?   _v_&z   'NcJ{(Hn{?_O6m       ?}3k7>?Q,
   -(d%4)   %172+   1;~+%~  ##Y.      #E2021
   m]};W=171;B=%{36<-~;%w~    ;puts   :Moo;'
   OAs"3$*2$-2"*5s}.bytes;   r=8;S=   ->*a{s
   v%3*17   0+1)*   w=v/3,  n-(S[s,v%3<1?n+w-z:w*W+z]
   &6,s+B   .pop-   34+v/3 *W])};S[2082,m=8378];c=[Z*
   =2;i%2>0?%q@_R=eval$q=%q{z=?\      s;eval
   *z)if[]==$*.map{|n|puts  (n.       match(
   q}":(m=n.to_i;f=->x{m>1 ?m%x<1?(m/=x;[x]+f[x]):f[x+
   )}}*""           }@[b+= 1]:Z}*""+Z*51}+c)*N;c=340;s
   t=T+""           ;b=0;M [2,x=D["^lv(2A"[i]]+3302+26
  "\e[F"*           47;504            .times
 &o[x]=c            };$><<            s+o.gs
#!;eval        n='eval q.             gsub((
  /[\s          ]|~.*$/)              ,"")#'
```

This is also executable. It prints `><`, which represents [a Greek letter Chi](https://en.wikipedia.org/wiki/Chi_(letter)).

```
$ ruby kai.rb
><
```


## Further decomposition of "kai.rb"

BTW, a letter ["解"](https://jisho.org/search/%E8%A7%A3%20%23kanji) is made of different Kanji letters: ["角"](https://jisho.org/search/%E8%A7%92%20%23kanji), ["刀"](https://jisho.org/search/%E5%88%80%20%23kanji), and ["牛"](https://jisho.org/search/%E7%89%9B%20%23kanji).
Therefore, "kai.rb" can be decomposed to "tsuno.rb", "katana.rb", and "ushi.rb", respectively.

### tsuno.rb

The left component is called "tsuno.rb".

```
       p="><"
      puts""+             
      "\u89D2";;x=(%~     
     .ljust(170)};D=->    
    ["cGIY&    ?dUptZ     
  XzIUF<+     <L-MlD      
 -m.size)+m.reverse];t[x]=
&&t[i]>Z&&F[i,[i]+m]}};M=-
  *?_jJc?   _v_&z   'NcJ{(
   -(d%4)   %172+   1;~+%~
   m]};W=171;B=%{36<-~;%w~
   OAs"3$*2$-2"*5s}.bytes;
   v%3*17   0+1)*   w=v/3,
   &6,s+B   .pop-   34+v/3
   =2;i%2>0?%q@_R=eval$q=%
   *z)if[]==$*.map{|n|puts
   q}":(m=n.to_i;f=->x{m>1
   )}}*""           }@[b+=
   t=T+""           ;b=0;M
  "\e[F"*           47;504
 &o[x]=c            };$><<
#!;eval        n='eval q. 
  /[\s          ]|~.*$/)  
```

This prints a letter [U+89D2](https://www.A.fileformat.info/info/unicode/char/89d2/index.htm).

```
$ ruby tsuno.rb
角
```

### katana.rb

"katana.rb" is the top-right component of "kai.rb".

```

p||$><<"____\n\s/\s/\n";(
);%#?_Y}_U1jojD(i0(DVA1aq
     e{d=0;e.      bytes{
      yGj5?=       1+wD5G
     )"+t[2        513,21
   Z;[1,-1        ,-W,W].
>d,x{y=x;    m=[];v=0;(m
n{?_O6m       ?}3k7>?Q,
 ##Y.
```

When it is executed, a simple ASCII art of the letter "刀" is printed.

```
$ ruby katana.rb
____
 / /
```

### ushi.rb

The bottom-right component is "ushi.rb".

```
           #E2021
   ;puts   :Moo;'
  r=8;S=   ->*a{s
 n-(S[s,v%3<1?n+w-z:w*W+z]
*W])};S[2082,m=8378];c=[Z*
{z=?\      s;eval
 (n.       match(
?m%x<1?(m/=x;[x]+f[x]):f[x+
1]:Z}*""+Z*51}+c)*N;c=340;s
[2,x=D["^lv(2A"[i]]+3302+26
           .times
           s+o.gs
           gsub((
           ,"")#'
```

The letter "牛" means "a cow" in Japanese. So "ushi.rb" does say:

```
$ ruby ushi.rb
Moo
```


## Additional bonus

The original program shows a banner "Solved". This banner is also an executable Ruby program.

```
   R=eval                  $q=                                   %q{
 z=?\s;eval                %w{                                   put
s(["     Usa               ge:                                   ",:
 ruby                      ,$0                                   ,10
   0]*z)if      []==$*.    map  {|n     |pu    ts(n.ma      tch(/q/)
       ?$q[    /^#   {z}   +/]  +z+     z+"   R=e   val    #{z   *18
}$q     =#{z  *35}   %q{#  $q}   ":(   m=n   .to_i;f=->x  {m>1   ?m%
 x<1?(m/=x;    [x]   +f[   x])    :f[ x+1     ]:[          ]};   n+z
   +?=+z+       (m>1?f[    2]:     [m])*       (z+?x+z)     ))}}*""}
```

### Prime decomposition

When executed with no argument, it explains how to use.

```
$ ruby solved.rb
Usage: ruby solved.rb 100
```

When executed with integer arguments, it does prime factorization (as known as prime *decomposition*).

```
$ ruby solved.rb 100
100 = 2 x 2 x 5 x 5

$ ruby solved.rb 1 2 3 4 5 6 7 8 9 10
1 = 1
2 = 2
3 = 3
4 = 2 x 2
5 = 5
6 = 2 x 3
7 = 7
8 = 2 x 2 x 2
9 = 3 x 3
10 = 2 x 5
```

### Final bonus

"solved.rb" prints "solved.rb" itself when executed with an argument ["quine"](https://en.wikipedia.org/wiki/Quine_%28computing%29).

```
$ ruby solved.rb quine
   R=eval                  $q=                                   %q{
 z=?\s;eval                %w{                                   put
s(["     Usa               ge:                                   ",:
 ruby                      ,$0                                   ,10
   0]*z)if      []==$*.    map  {|n     |pu    ts(n.ma      tch(/q/)
       ?$q[    /^#   {z}   +/]  +z+     z+"   R=e   val    #{z   *18
}$q     =#{z  *35}   %q{#  $q}   ":(   m=n   .to_i;f=->x  {m>1   ?m%
 x<1?(m/=x;    [x]   +f[   x])    :f[ x+1     ]:[          ]};   n+z
   +?=+z+       (m>1?f[    2]:     [m])*       (z+?x+z)     ))}}*""}
```
