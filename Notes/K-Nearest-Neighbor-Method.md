# Summary
  - K-NN: k-nearest neighbor
  - Three Basic Elements
    - Distance Metric
    
    <a href="https://www.codecogs.com/eqnedit.php?latex=L_p(x_i,x_j)=(\sum_{l=1}^{n}|x_i^{(l)}-x_j^{(l)}|^p)^{\frac{1}{p}}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?L_p(x_i,x_j)=(\sum_{l=1}^{n}|x_i^{(l)}-x_j^{(l)}|^p)^{\frac{1}{p}}" title="L_p(x_i,x_j)=(\sum_{l=1}^{n}|x_i^{(l)}-x_j^{(l)}|^p)^{\frac{1}{p}}" /></a>
    
    > notes: 
    
    Euclidean Distance: <a href="https://www.codecogs.com/eqnedit.php?latex=L_2(x_i,x_j)=(\sum_{l=1}^{n}|x_i^{(l)}-x_j^{(l)}|^2)^{\frac{1}{2}}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?L_2(x_i,x_j)=(\sum_{l=1}^{n}|x_i^{(l)}-x_j^{(l)}|^2)^{\frac{1}{2}}" title="L_2(x_i,x_j)=(\sum_{l=1}^{n}|x_i^{(l)}-x_j^{(l)}|^2)^{\frac{1}{2}}" /></a>
    
    Manhattan Distance: <a href="https://www.codecogs.com/eqnedit.php?latex=L_1(x_i,x_j)=\sum_{l=1}^{n}|x_i^{(l)}-x_j^{(l)}|" target="_blank"><img src="https://latex.codecogs.com/gif.latex?L_1(x_i,x_j)=\sum_{l=1}^{n}|x_i^{(l)}-x_j^{(l)}|" title="L_1(x_i,x_j)=\sum_{l=1}^{n}|x_i^{(l)}-x_j^{(l)}|" /></a>
    
    $p=\infty$, <a href="https://www.codecogs.com/eqnedit.php?latex=L_\infty&space;(x_i,x_j)=\underset{l}{max}|x_i^{(l)}-x_j^{(l)}|" target="_blank"><img src="https://latex.codecogs.com/gif.latex?L_\infty&space;(x_i,x_j)=\underset{l}{max}|x_i^{(l)}-x_j^{(l)}|" title="L_\infty (x_i,x_j)=\underset{l}{max}|x_i^{(l)}-x_j^{(l)}|" /></a>
    
    - Choice Of k Value
    
    > notes: When the $k$ value is small, the k-nearest neighbor model is more complicated; when the $k$ value is large, the k-nearest neighbor model is simpler. The choice of $k$ value reflects the trade-off between the approximation error and the estimation error. When the $k$ value decreases, the approximation error decreases and the estimation error increases. When the $k$ value increases, the approximation error increases and the estimation error decreases. The optimal $k$ is usually chosen by cross-validation.
