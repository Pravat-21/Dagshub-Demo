### If you want to log_model with dagshub then you must install
```
pip install "mlflow<3"
```
- our log_model fucntion looks like--
```
mlflow.sklearn.log_model(dt,"Decision tree",input_example=X_train)
```
then only it will execute successfully otherwise through error.
_______________________________________________________________________________________