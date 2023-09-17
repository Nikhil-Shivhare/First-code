# First-code a =int (input ("rom rom bhaiyo "))
for m in range(1,a+1):
    for n in range (a,0,-1):
        if (n>m):
            print( '',end=('   '))
        else:
            print('',end=(' # '))    
    print('')        
# agar mai sirf upar wala bas run karu gaa to inverted triagle print hoga
for m in range(1,a+1):
    for n in range (a,0,-1):
        if (n>m):
            print( '',end=(' # '))
        else:
            print('',end=('  '))    
    print('')     
