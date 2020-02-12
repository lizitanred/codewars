# Who likes this?

def likes(names):

    for i in range(len(names)):
        print('Please type the ' + )
    len_names = len(names)
    if len(names) == 0:
        return ('no one likes this')
    elif len(names) == 1:
        return (names[0] + ' likes this')
    elif len(names) == 2:
        return (names[0] + ' and ' + names[1] + ' likes this')
    elif len(names) == 3:
        return (names[0] + ', ' + names[1] + ' and ' + names[2] + ' like this')
    elif len(names) >=4:
        return (names[0] + ', ' + names[1] + ' and '+str(len_names-2)+' others like this')
