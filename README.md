 study1
 ================

알고리즘을 위한 파이썬 공부1
---------------------------

#함수익히기1

split
<pre>
<code>
#sequence.split()형태로 쓴다 괄호 안을 기준으로 문자열을 나눈다.
#아무것도 쓰지 않으면 공백을 기준으로 나눈다.
str = I Love You
list = str.split()  
>>>list = [I,Love,You]
</pre>
</code>

join
<pre>
<code>
#ex) ','.join(sequence) : 문자 ','를 넣으며 시퀀스를 합친다.
list = [1,2,3,4]

list = ','.join(list)
>>> list = '1,2,3,4'

list = ' '.join(list)
>>> list = '1 2 3 4'

list =''.join(list)
>>> list = '1234'
</pre>
</code>

count
<pre>
<code>
# sequence.count('String') : 시퀀스에서 괄호 안의 String이 몇 번 들어갔는지 세어준다.
str = java
str = str.count('a')
>>> str = 2
list = [1,1,2,3,3,3]
list = list.count(3)
>>> list = 3
</pre>
</code>

len
<pre>
<code>
# len(sequence) : 시퀀스의 길이를 구해준다.
a = len('tiger')
>>> 5
len([1,2,3,4,5])
>>> 5
</code>
</pre>

ㅣ










