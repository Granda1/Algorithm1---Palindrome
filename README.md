# Algorithm1---Palindrome
'''
1: 유효한 팰린드롬(Palindrome)

문제
    주어진 문자열이 팰린드롬인지 확인하라.
대소문자를 구분하지 않으며, 영문자와 숫자만을 대상으로 한다.

*Palindrom이란, 앞뒤가 똑같은 단어나 문장을 말한다.
'''

a = list('A man, a plan, a canal: Panama !')
b = [x.lower() for x in a if x.isalnum()]
c = list(reversed(b))

def ispalin(b,c) -> bool:
    if b == c:
        return True
    else:
        return False

print(ispalin(b,c))
