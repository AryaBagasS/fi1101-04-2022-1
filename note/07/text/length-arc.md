# length-arc
calculate length of an arch


## equation of circle
Persamaan suatu lingkaran yang berpusat di $(0, 0)$ diberikan oleh

$$\tag{1}
x^2 + y^2 = R^2,
$$

yang dapat dibuat menjadi

$$\tag{2a}
y = \sqrt{R^2 - x^2}
$$

untuk bagian atas dan

$$\tag{2b}
y = -\sqrt{R^2 - x^2}
$$

untuk bagian bawah.

Atau dapat pula dalam bentuk persamaan parametrik

$$\tag{3a}
x = R \cos \omega t
$$

untuk $x$ dan

$$\tag{3b}
y = R \sin \omega t
$$

untuk $y$.


## curve length
Panjang busur dari Persamaan (2a) dan (2b) dapat dihitung dengan

$$\tag{4}
L = \int ds = \int \sqrt{1 + \left(\frac{dy}{dt}\right)^2}  dt = \int \sqrt{1 + \left(\frac{dy}{dx}\right)^2} dx,
$$

menggunakan $x = t$, sedangkan dari Persamaan (3a) dan (3b) dapat dihitung dengan

$$\tag{5}
L = \int ds = \int \sqrt{\left(\frac{dx}{dt}\right)^2 + \left(\frac{dy}{dt}\right)^2} dt.
$$


## polar coordinate
Elemen panjang busur lingkaran dalam koordinat polar

$$\tag{6}
L = \int ds = \int R  d\theta,
$$

dengan batas integralnya adalah $\theta_i$ dan $\theta_f$ sebagai sudut awal dan akhir.


## discussion
1. Dari Persamaan (4), (5), dan (6) mana yang lebih mudah untuk menghitung panjang busur suatu lingkaran? Jelaskan alasannya.