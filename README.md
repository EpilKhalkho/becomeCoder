#become_coder
#harshad_number
def har( n ):
    sum = 0
    temp = n
    while temp > 0 :
        sum = sum + temp % 10
        temp = temp // 10
    if n % sum == 0:
        return 'False'
    return 'True'
    
 
n=int(input())
print(har(n))
 
