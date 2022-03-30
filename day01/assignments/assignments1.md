### Exercise 1:

- Implement C or Fortran version for the code below

```python
do i =1 , N * i_stride , i_stride
   mean = mean + a ( i )
end do
```
- Compute the cpu time and bandwith for different stride (1 to 20) and plot the results
- We compile the above Fortran code with all optimization and vectorization disabled (-O0) and we run it for different strides
- We do the same thing, with (-O2) that activates some optimizations

- Expecting output:

![](strides_cputime.png)

![](strides_bandwidth.png)


### Exercise 2:

-


- Expecting output:

![](mxm_block_cputime.png)

![](mxm_block_bandwidth.png)
