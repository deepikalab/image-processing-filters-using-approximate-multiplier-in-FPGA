# image-processing-filters-using-approximate-multiplier
In this project I have implemented an approximate multiplier in FPGA using Verilog that can be used for image processing applications and compared the multiplier's performance with the Raspberry-Pi for the same application
 This multiplier using successive logarithmic
converters, features complete elimination of the arithmetic operation
of “multiplication”. This approach is power efficient and area
efficient with some tolerance for error. This multiplier manipulates
the logarithmic arithmetic and improves the architecture for the
realization of transcendental functions such as squaring, log, square
root etc. (non-algebraic functions). All computations in image
processing filters make use of these transcendental functions hence,
image processing filters can be implemented in FPGA. The image
processing filters are designed in the FPGA Nexys A7.The image to
be processed is sent in the binary form to the FPGA and convolved
with the above-mentioned filters and image is processed. Also, the
image processing operations are performed in the Raspberry pi 3.
This way, our project offers a comparison in the image processing
performance between an FPGA (Hardware) and RaspberryPi
(Software).
I have provided source codes for the Multiplier code(verilog),Additional modules designed to do other operations,filters(verilog),pixel conversion into coefficients(Matlab code),
