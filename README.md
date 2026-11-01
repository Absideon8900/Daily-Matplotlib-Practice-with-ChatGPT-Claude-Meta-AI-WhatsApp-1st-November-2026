# Daily Matplotlib Practice with ChatGPT, Claude, Meta AI (WhatsApp) 1st November 2026

# Solution (Script) Part 01 for Bar Graph
```Python
import matplotlib.pyplot as plt

x = [0,1,2,3,4,5,6,7,8,9,10,11]
y = [10, 20, 30, 40, 50, 60, 70, 80, 90, 100, 110, 120]
plt.grid(color="grey",linestyle="--",linewidth=0.5,alpha=1)
plt.style.use("dark_background")
plt.title("Test",color="white",fontweight="bold",fontfamily="arial")
plt.xlabel("X-axis",color="white",fontweight="bold",fontfamily="arial")
plt.ylabel("Y-axis",color="white",fontweight="bold",fontfamily="arial")
plt.bar(x, y,color=["#30123b",
                    "#4455c4",
                    "#4390fe",
                    "#1fc9dd",
                    "#2aefa1",
                    "#7eff55",
                    "#c2f234",
                    "#f2c93a",
                    "#fe8f29",
                    "#e94d0d",
                    "#bd2002",
                    "#7a0403"])
plt.text(0,10,"10",ha="center",va="bottom",color="white",fontweight="bold",fontfamily="arial")
plt.text(1,20,"20",ha="center",va="bottom",color="white",fontweight="bold",fontfamily="arial")
plt.text(2,30,"30",ha="center",va="bottom",color="white",fontweight="bold",fontfamily="arial")
plt.text(3,40,"40",ha="center",va="bottom",color="white",fontweight="bold",fontfamily="arial")
plt.text(4,50,"50",ha="center",va="bottom",color="white",fontweight="bold",fontfamily="arial")
plt.text(5,60,"60",ha="center",va="bottom",color="white",fontweight="bold",fontfamily="arial")
plt.text(6,70,"70",ha="center",va="bottom",color="white",fontweight="bold",fontfamily="arial")
plt.text(7,80,"80",ha="center",va="bottom",color="white",fontweight="bold",fontfamily="arial")
plt.text(8,90,"90",ha="center",va="bottom",color="white",fontweight="bold",fontfamily="arial")
plt.text(9,100,"100",ha="center",va="bottom",color="white",fontweight="bold",fontfamily="arial")
plt.text(10,110,"110",ha="center",va="bottom",color="white",fontweight="bold",fontfamily="arial")
plt.text(11,120,"120",ha="center",va="bottom",color="white",fontweight="bold",fontfamily="arial")
plt.show()
```
# Solution (Solution) Part 01 for Bar Graph
<img width="571" height="452" alt="image" src="https://github.com/user-attachments/assets/297be3ec-2664-4843-abaf-8f23e379fc63" />

# Solution (Script) Part 02 for Line Graph
```Python
import matplotlib.pyplot as plt

x = [0,1,2,3,4,5,6,7,8,9,10,11]
y = [10, 20, 30, 40, 50, 60, 70, 80, 90, 100, 110, 120]
plt.grid(color="grey",linestyle="--",linewidth=0.5,alpha=1)
plt.style.use("dark_background")
plt.title("Test",color="white",fontweight="bold",fontfamily="arial")
plt.xlabel("X-axis",color="white",fontweight="bold",fontfamily="arial")
plt.ylabel("Y-axis",color="white",fontweight="bold",fontfamily="arial")
plt.plot(x, y,color="white",linestyle="--",linewidth=1)
plt.text(0,10,"10",ha="center",va="bottom",color="white",fontweight="bold",fontfamily="arial")
plt.text(1,20,"20",ha="center",va="bottom",color="white",fontweight="bold",fontfamily="arial")
plt.text(2,30,"30",ha="center",va="bottom",color="white",fontweight="bold",fontfamily="arial")
plt.text(3,40,"40",ha="center",va="bottom",color="white",fontweight="bold",fontfamily="arial")
plt.text(4,50,"50",ha="center",va="bottom",color="white",fontweight="bold",fontfamily="arial")
plt.text(5,60,"60",ha="center",va="bottom",color="white",fontweight="bold",fontfamily="arial")
plt.text(6,70,"70",ha="center",va="bottom",color="white",fontweight="bold",fontfamily="arial")
plt.text(7,80,"80",ha="center",va="bottom",color="white",fontweight="bold",fontfamily="arial")
plt.text(8,90,"90",ha="center",va="bottom",color="white",fontweight="bold",fontfamily="arial")
plt.text(9,100,"100",ha="center",va="bottom",color="white",fontweight="bold",fontfamily="arial")
plt.text(10,110,"110",ha="center",va="bottom",color="white",fontweight="bold",fontfamily="arial")
plt.text(11,120,"120",ha="center",va="bottom",color="white",fontweight="bold",fontfamily="arial")
plt.show()
```
# Solution (Solution) Part 02 for Line Graph
<img width="571" height="452" alt="image" src="https://github.com/user-attachments/assets/9ba07b35-add1-442e-b469-fd7c54395392" />
