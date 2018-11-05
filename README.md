
# This code is meant to evaluate a string.
s = 'he?LLo'

def check_word(s):    __this checks to see if the variable is a string__
    if isinstance(s,str):
        pass
    else:
        print("This is not a string")


def strip_pun(s):    __this strips the question mark from s__
    s_stripped = s.replace('?','')
    #print(s_stripped)
    get_rev(s_stripped)


def get_rev(s):    __this puts the string in reverse__
    s_rev = s[::-1]
    #print(s_rev)
    make_lower(s_rev)

def make_lower(s):    __this makes the string lowercase__
    s_low = s.lower()
    find_len(s_low)
    
    
def find_len(s):    __this finds the length of the string__
    length = len(s)
    print(length)

def main():
    check_word(s)
    strip_pun(s)
    get_rev(s)
    make_lower(s)
    find_len(s)
    


if __name__ == '__main__':
    main()
