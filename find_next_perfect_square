import math
def find_next_square(sq):
    # Return the next square if sq is a square, -1 otherwise
    if math.sqrt(sq).is_integer():
        sq += 1
        while math.sqrt(sq).is_integer() == False:
            sq += 1
        else:
            return sq
    else:
        return -1
