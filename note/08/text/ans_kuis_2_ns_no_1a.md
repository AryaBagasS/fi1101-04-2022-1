# ans_2a
Mencari $v_{0x}$ dan $v_{0y}$ dengan posisi awal $x(0) = x_0 = 0$ dan $y(0) = y_0 = 0$


## mencari $v_{0y}$
Dari grafik di kanan atas dapat diperoleh fungsi

$$\tag{1}
v_y(x) = -0.5(x - 10).
$$

Kecepatan awal bola pada arah vertikal diberikan pada posisi $x = 0$, sehingga


$$\tag{2}
v_{0y} = 5
$$


## mencari $v_{0x}$
Terdapat dua cara untuk mendapatkan $v_{0x}$.

### cara pertama
Menggunakan aturan rantai pada kalkulus dan informasi dari grafik.

Kecepatan para arah x diperoleh

$$
\begin{array}{rcl}
v_x & = & \displaystyle \frac{dx}{dt} \newline
& = & \displaystyle \frac{dx}{dv_y} \frac{dv_y}{dt} \newline
& = & \displaystyle \frac{dx}{dv_y} \frac{d^2 y}{dt^2} \newline
& = &  (-0.5)^{-1} \ (-10) = 20.
\end{array}
$$

Dan karena pada arah $x$ adalah GLB maka $v_{0x} = v_x$.


### cara kedua
Menggunakan informasi dari grafik dan persamaan-persamaan kinematika pada arah $x$ dan $y$. Bola mencapai puncak parabola saat $v_y = v_{y,p} = 0$ yang diperoleh pada posisi

$$\tag{3}
x_p = 10.
$$

Posisi horizontal setiap saat diberikan oleh

$$\tag{4}
x(t) = 0 + v_{0x} \ t
$$

dan posisi vertikal setiap saat

$$\tag{5}
y(t) = 0 + v_{0y} \ t + \tfrac12 a_yt^2.
$$

Dari informasi (2) dan (5) serta $a_y = g = -10$ diperoleh

$$\tag{6}
y(t) = 5 t - 5t^2 = 5t(1 - t),
$$

yang memberikan bahwa benda berangkat dari $O(0, 0)$ saat $t = 0$ dan kembali ke tanah saat $t = 1$, sehingga waktu di puncak adalah

$$\tag{7}
t_p = \frac{1 - 0}{2} = 0.5.
$$

Substitusi hasil Persamaan (3) dan (7) ke Persamaan (4) akan memberikan

$$
v_{0x} = \frac{10}{0.5} = 20.
$$