# Gaussian_Hump_Hankel_Solution
Numerical Solution of Propagation of Gaussian Hump over constant depth


Linear Shallow Water Equation:

![equation](https://latex.codecogs.com/svg.latex?\nabla^{2}%20\eta(\boldsymbol{r},%20t)-\frac{1}{c^{2}}%20\frac{\partial^{2}%20\eta(\boldsymbol{r},%20t)}{\partial%20t^{2}}=0)

Initial Conditions:

![equation](https://latex.codecogs.com/svg.latex?\left.\eta(\boldsymbol{r},%20t)\right|_{t=0}=\eta_{0}(\boldsymbol{r})%20\quad\quad\quad\left.\frac{\partial%20\eta(\boldsymbol{r},%20t)}{\partial%20t}\right|_{t=0}=0)

Gaussian Hump:

![equation](https://latex.codecogs.com/svg.latex?\eta_{0}(r)=a_{0}\exp%20\left(-\frac{2%20r^{2}}{\lambda_{0}^{2}}\right))

Hankel transform:

![equation](https://latex.codecogs.com/svg.latex?\hat{\eta}_{0}(s)%20=\mathcal{H}_{0}\left\{\eta_{0}(r)\right\}=\mathcal{H}_{0}\left\{a_{0}\exp%20\left(-\frac{2%20r^{2}}{\lambda_{0}^{2}}\right)\right\}%20=%20\frac{a_{0}\lambda_{0}^{2}}{4}%20\exp%20\left(-\frac{\lambda_{0}^{2}%20s^{2}}{8}\right))

