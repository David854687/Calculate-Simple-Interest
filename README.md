# Calculate-Simple-Interest
def simple_interest(p, t, r):
    """
    p = principal amount
    t = time interval
    r = rate of interest
    
    si = simple interest given p, t, r
    """
      
    si = (p * t * r)/100
      
    print("The Simple Interest is", si)
    return si
    
simple_interest(1200, 10, 7)
