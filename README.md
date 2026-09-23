# -*- coding: utf-8 -*-
"""
Created on Wed Sep 23 08:18:41 2026

@author: user
"""

t=(10,20,20,30,40)
print("tuple:",t)
print("First element:",t[0])
print("Last element:",t[-1])
print("Length:",len(t))
print("count of 20:",t.count(20))
print("Index of 30:",t.index(30))
print("Maximun:",max(t))
print("Minimum:",min(t))
print("Sum:",sum(t))
print("Is 40 present?:",40 in t)
# convert tuple to list
l=list(t)
print("Touple converrted to list:",l)
# convert list back to touple
t2 =tuple(l)
print("List converted to touple: ",t2)
