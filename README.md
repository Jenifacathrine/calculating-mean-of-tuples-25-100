# calculating-mean-of-tuples
tp1 = eval(input("Enter tuple: "))
length = len(tp1)
total_sum = 0

for i in range(length):
    total_sum += tp1[i]

mean = total_sum / length

print("Given tuple is:", tp1)
print("The mean of the given tuple is:", mean)
