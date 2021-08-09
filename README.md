# Clasificación
## qqplots accuracy entrenamiento y validación

![qqplots](../classplots/qqplot-acc-training.png "Accuracy training results")
![qqplots](../classplots/qqplot-acc-validation.png "Accuracy validation results")

## Tabla de accuracy

Mean and standard deviation for the obtained accuracy for training and validation of text classification. By using all components of text better results are achieved.

<table>
<thead>
  <tr>
    <th rowspan="2">Used components</th>
    <th colspan="2">Training set</th>
    <th colspan="2">Validation set</th>
  </tr>
  <tr>
    <td>&mu;</td>
    <td>&sigma;</td>
    <td>&mu;</td>
    <td>&sigma;</td>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Full</td>
    <td><b>0.8706<b></td>
    <td>0.0371</td>
    <td><b>0.5325<b></td>
    <td>0.0765</td>
  </tr>
  <tr>
    <td>Lexical-Syntactic</td>
    <td>0.7121</td>
    <td>0.0376</td>
    <td>0.4912</td>
    <td>0.0687</td>
  </tr>
  <tr>
    <td>Lexical-Semantic</td>
    <td>0.8045</td>
    <td>0.0402</td>
    <td>0.5020</td>
    <td>0.0707</td>
  </tr>
  <tr>
    <td>Syntactic-Semantic</td>
    <td>0.8579</td>
    <td>0.0413</td>
    <td>0.4820</td>
    <td>0.0716</td>
  </tr>
  <tr>
    <td>Lexical</td>
    <td>0.4654</td>
    <td>0.0270</td>
    <td>0.4504</td>
    <td>0.0626</td>
  </tr>
  <tr>
    <td>Syntactic</td>
    <td>0.6701</td>
    <td>0.0495</td>
    <td>0.4772</td>
    <td>0.0703</td>
  </tr>
  <tr>
    <td>Semantic</td>
    <td>0.8067</td>
    <td>0.0574</td>
    <td>0.4926</td>
    <td>0.0748</td>
  </tr>
</tbody>
</table>

## t-test accuracy
    
T-test results from the experiments. In all cases the p-value < .05, which reflects that there is a significant difference of accuracy between using all components of text and using one or two of them. Confidence intervals of the difference between means also reflect a positive difference in all cases showing also that higher accuracy values are reached by using all components simultaneously.
                                                                    
- Tabla de precision (micro y macro)
- t-test precision (micro y macro)
- Tabla de recall (micro y macro)
- t-test recall (micro y macro)
- Tabla de F-1 (micro y macro)
- t-test F-1 (micro y macro)


# Regresión
- qqplots