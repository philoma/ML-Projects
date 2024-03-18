# KDE
If you're looking for a powerful tool for data visualization, KDE is definitely worth considering. With its ability to represent each data point as a bell curve and then sum it up to produce an effective graph, it's an excellent choice for analyzing complex datasets. And the best part? You can use any Kernel, such as triangular, cosine, sine, or Gaussian Kernel, to customize your graphs. In fact, Gaussian Kernel is the default Kernel in seaborn, making it a great starting point for your data analysis needs. Give it a try and see how KDE can help you visualize your data in a whole new way.

Each data point is represented as a bell curve (aka kernel) and then summed up together to produce final graph.

For KDE, we can use any Kernel (triangular, cosine, sine, Gaussian Kernel), in seaborn, Gaussian Kernel is a default Kernel

https://www.youtube.com/watch?v=DCgPRaIDYXA

# Kernel:
Kernel is simply a function which satisfies following three properties as mentioned below:
1. The first property of a kernel function is that it must be symmetrical.
   
   ![image](https://github.com/philoma/ML-Projects-Notebooks/assets/87674698/d14d057c-376e-4285-822e-bff3bad90980)

2. The area under the curve of the function must be equal to one.
   
   ![image](https://github.com/philoma/ML-Projects-Notebooks/assets/87674698/4e66c121-26e6-4d0e-a9bb-88dda9ca2e4b)
3. The value of kernel function, which is the density, can not be negative, K(u) ≥ 0 for all −∞ < u < ∞.

   <a href='https://medium.com/analytics-vidhya/kernel-density-estimation-kernel-construction-and-bandwidth-optimization-using-maximum-b1dfce127073#:~:text=Kernel%20functions%20are%20used%20to,that%20it%20must%20be%20symmetrical.> Ref. </a>
