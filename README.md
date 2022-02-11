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
str = 'java'
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

find
<pre>
<code>
# String.find() : 괄호 안의 문자가 처음 나온 인덱스를 알려준다.
# 만약에 없다면 -1을 반환한다.
# 리스트, 튜플, 딕셔너리 자료형에서는 find 함수를 사용할 수 없다. 만일 사용하게 되면 AttributeError 에러가 발생한다.
# cf) index 함수도 동일한 기능을 하지만 찾는 문자열이 없으면 -1을 반환하는 find와는 달리 ValueError가 발생한다.

str = 'java'
str.find(a) #1

</code>
</pre>

upper
<pre>
<code>
# String.upper() : 소문자를 대문자로 바꿔준다

str = 'Love'
str.upper() #LOVE
</code>
</pre>


lower
<pre>
<code>
# String.lower() : 대문자를 소문자로 바꿔준다.

str = 'Love'
str.lower() #love
</code>
</pre>




















