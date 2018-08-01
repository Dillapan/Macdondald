# Macdondald
a = []
def function(s):
    for element in s:
        if element >= 2:
            a.append(element)
        else:
            a.pop(a[0])
function(22)
