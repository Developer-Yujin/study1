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
list = [I,Love,You]
</pre>
</code>

join
<pre>
<code>
#ex) ','.join(sequence) : 문자 ','를 넣으며 시퀀스를 합친다.
list = [1,2,3,4]

','.join(list)
>>> list = '1,2,3,4'

' '.join(list)
>>> list = '1 2 3 4'

''.join(list)
>>> list = '1234'
</pre>
</code>









