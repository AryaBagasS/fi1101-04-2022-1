# length-arch-exmp-1
calculate arch length


## example 1
Hitunglah panjang busur lingkaran bagian atas dari persamaan lingkaran $x^2 + y^2 = R^2$ dari $x = 0$ sampai $x = R$.

Dengan persamaan bagian atas busur lingkaran

$$\tag{1}
y = \sqrt{R^2 - x^2},
$$

dapat diperoleh

$$\tag{2}
\begin{array}{rcl}
\displaystyle \frac{dy}{dx} & = & \displaystyle \frac{d}{dx} \sqrt{R^2 - x^2} \newline
& = & \frac12 \cdot (R^2 - x^2)^{-\frac12} \cdot -2x \newline
& = & \displaystyle -\frac{x}{\sqrt{R^2 - x^2}},
\end{array}
$$

yang selanjutnya menjadi

$$\tag{3}
\left( \frac{dy}{dx} \right)^2 = \frac{x^2}{R^2 - x^2}.
$$

Terdapat integral

$$\tag{4}
\begin{array}{rcl}
\displaystyle \int \sqrt{1 + \left( \frac{dy}{dx} \right)^2} dx & = & \displaystyle \int \sqrt{1 + \frac{x^2}{R^2 - x^2}} dx \newline
& = & \displaystyle \int \sqrt{\frac{R^2}{R^2 - x^2}} dx \newline
& = & \displaystyle R \int \frac{dx}{\sqrt{R^2 - x^2}}.
\end{array}
$$

Bagian akhir, di dalam integral, Persamaan (4) perlu dipecahkan terlebih dahulu.
