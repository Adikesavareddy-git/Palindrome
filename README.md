def palindrome(s):
       return s==s[::-1]
s = "KISSIK"
ans =  palindrome(s)
if ans:
      print("This is Palindrome")
else:
     print("This is not Palindrome")
