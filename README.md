# Author: Michelle Frugia
# GitHub username: frugiam
# Date: 02/14/2024
# Description: Project 6a

def find_median(lst):
    lst.sort()
    if(len(lst) %2 == 1):
        return lst[len(lst)//2]
    else:
        return (lst[len(lst) // 2-1] + lst[len(lst) // 2])/2
