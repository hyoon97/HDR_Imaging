# HDR_Imaging

## LINEARIZE RENDERED IMAGES
This work is to linearize the rendered image which is non-linear. To achieve my goal , I have to solve least squares optimization problem.
The result shows each gradient curve using uniform, tent, gaussian weight scheme for each color channels, respectively. 
As shown below, the gradient curve with gaussian weight scheme is the more smooth than other curves 
<table>
    <tr>
        <th>Weight: Uniform</th>
        <th>Weight: Tent</th>
        <th>Weight: Gaussian</th>
    </tr>
    <tr>
        <td><img src='./img/gradient_curve_uniform.png'></td>
        <td><img src='./img/gradient_curve_tent.png'></td>
        <td><img src='./img/gradient_curve_gaussian.png'></td>
    </tr>
</table>

## MERGE EXPOSURE STACK INTO HDR IMAGE



## EVALUATION

# TONEMAPPING

## PHOTOGRAPHIC TONEMAPPING

## TONEMAPPING USING BILATERAL FILTERING
