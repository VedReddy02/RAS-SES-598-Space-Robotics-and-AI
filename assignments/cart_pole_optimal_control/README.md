Final LQR parameters

Q = [ 1.0 , 3.0 , 1.0 , 3.0]
R = [0.1]

Approach taken to arrive at this conclusion

1. Initial parameters are Q = [ 1.0 , 1.0 , 10.0 , 10.0]
2. setting "x" to 2 made the cart pole to move rapidly and the pole fell instantly
3. Changed "x" back to 1 and changed "x_dot" to 2, this made the cart pole balance for a relatively longer time but the position of the cart moved rapidly
4. "X_dot"  was increased to 3, this resulted in minimal position movement and also the system was balanced for a long time
5. Then started tuning the "theta" parameters. "theta" was set to 5. this resulted in movement along the position of the cart and resulted in falling of the pole
6. To conter this "theta" was increased to 15. This made the cart balance but the system created a wiggly motion
7. "theta_dot" was increased to 20, this made the pole fall instantly
8. the next step was to decrease both "theta" amd "theta_dot". "theta" was set to 5 and "theta_dot" to 10, this made the cart pole well balanced but a little movement in position
9. finally "theta" and "theta_dot" were set to 1 and 3. This made the cart pole well balanced
   
