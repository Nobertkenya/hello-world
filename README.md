def nested_example(x):
    if x < 50:
        if x % 2 == 0:
            return 'Nobert'
        else:
            return 'Winnie '

    else:
        return 'Nolan'
print(nested_example(20))
print(nested_example(37))
print(nested_example(61))
  
