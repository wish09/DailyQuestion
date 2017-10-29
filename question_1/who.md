在使用 for 循环迭代一个列表时，有时我们需要获取列表中每个元素所在的下标位置是多少，例如 numbers = [10, 29, 30, 41]，要求输出 (0, 10)，(1, 29)，(2, 30)，(3, 41)


    numbers = [10, 29, 30, 41]
    items = [(x, y) for x, y in enumerate(numbers)]
    for item in items:
        print(item)