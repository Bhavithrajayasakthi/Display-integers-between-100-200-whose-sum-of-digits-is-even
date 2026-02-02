# Display-integers-between-100-200-whose-sum-of-digits-is-even
def even_digit_sum_numbers():
    for i in range(100, 201):
        num = i
        total = 0

        while num != 0:
            digit = num % 10
            total = total + digit
            num = num // 10

        if total % 2 == 0:
            print(i)

even_digit_sum_numbers()
Output

100
102
104
106
108
110
112
114
116
118
120
...
198
200
