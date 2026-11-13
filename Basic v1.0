import matplotlib.pyplot as plt
from matplotlib.ticker import MaxNLocator



n = int(input("Enter an amount of numbers: "))
x = []
y = []
for _ in range(1, n + 1):
    xappend = int(input("Enter a number for x: "))
    x.append(xappend)
    yappend = int(input("Enter a number for y: "))
    y.append(yappend)
    
typeof = input("Enter a type of graph (line, scatter, bar): ").lower()
color = input("Enter a color of line: ")
gridi = input("Grid True or False: ").lower() == "true" 
titlex = input("Title: ")
xtitle = input("Text on x: ")
ytitle = input("Text on y: ")
if typeof == "line":
    plt.plot(x, y, color = color)
elif typeof == "scatter":
    plt.scatter(x, y, color = color)
elif typeof == "bar":
    plt.bar(x, y, color = color)
else:
    print("Invalid type of graphic")
    exit()
plt.grid(gridi)
plt.title(titlex)
plt.xlabel(xtitle)
plt.ylabel(ytitle)
plt.gca().xaxis.set_major_locator(MaxNLocator(integer=True))
plt.gca().yaxis.set_major_locator(MaxNLocator(integer=True))
plt.show()

print(x)
print(y)
