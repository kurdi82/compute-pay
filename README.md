def computepay(h,r):
    pay = h * r
    if pay <= 40:
        pay = h * r
    elif pay >= 40:
        pay = (40 * r) + (h-40) * (r * 1.5)
    return pay

hrs = input("Enter hours")
rte = input("Enter rate")
h = float(hrs)
r = float(rte)

p = computepay(h,r)
print(p)
