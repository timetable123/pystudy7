# pystudy7
==============================================================================================================================
# 수열
r = 1

for i in range(30):
    print(r)
    r *= 2
    
==============================================================================================================================    
# 쌀한톨
r = 1
s = 0
for i in range(30):
    s += r
    r *= 2

print(s/40000)

==============================================================================================================================
#  구구단
s = 5
for i in range(1, 10):
    w = '{}*{}={}'.format(s,i,s*i) # format 함수를 이용해 더욱 쉽게 작성

    print(w)
    
==============================================================================================================================
# 숫자 피라미드
n = '123456789'
for i in range(9):
    s=n[:i+1]
    w='{0:>9s}*8+{1}={2}'.format(s, i+1, int(s)*8+i)
    print(w)
    
==============================================================================================================================
# 부호바꾸기 출력
n = 10
f = 1
for i in range(1, n+1):
    print(f*i)
    f = -f

==============================================================================================================================
# 근사치
n = 10000000
f = 1
s = 0
for i in range(1, n+1):
    s = s+f*1/i
    f=-f

print(s)

==============================================================================================================================
# 단축 근사치
n = 10000000
f,s = 1, 0
for i in range(1, n+1):
    s += f/(2*i-1)
    f=-f

print(4*s)





















