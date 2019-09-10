# local Linear Regression

## Dependencies
- sklearn
- numpy

## steps to use
### import libs
```
from sklearn.linear_model import LinearRegression
import numpy as np
```

### load dataset
get X_train, Y_train, X_test, Y_test

### define an object
```
foo =LWLR(k=1)
```
### fit dataset

```
foo.fit(X_train,y_train)
```
### predict test data
```
preds=foo.predict(X_test)
```