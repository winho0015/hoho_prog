# hoho_prog
def solution(sides):
    maxS = sides.pop(sides.index(max(sides)))
    if maxS < (sum(sides)):
        return 1
    else:
        return 2
