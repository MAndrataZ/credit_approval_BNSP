## Error for 4_Default_LightGBM

exception: access violation reading 0x0000000000000000
Traceback (most recent call last):
  File "c:\Users\Lenovo\AppData\Local\Programs\Python\Python310\lib\site-packages\supervised\base_automl.py", line 1209, in _fit
    trained = self.train_model(params)
  File "c:\Users\Lenovo\AppData\Local\Programs\Python\Python310\lib\site-packages\supervised\base_automl.py", line 399, in train_model
    mf.train(results_path, model_subpath)
  File "c:\Users\Lenovo\AppData\Local\Programs\Python\Python310\lib\site-packages\supervised\model_framework.py", line 249, in train
    learner.fit(
  File "c:\Users\Lenovo\AppData\Local\Programs\Python\Python310\lib\site-packages\supervised\algorithms\lightgbm.py", line 236, in fit
    self.model = lgb.train(
  File "c:\Users\Lenovo\AppData\Local\Programs\Python\Python310\lib\site-packages\lightgbm\engine.py", line 296, in train
    booster = Booster(params=params, train_set=train_set)
  File "c:\Users\Lenovo\AppData\Local\Programs\Python\Python310\lib\site-packages\lightgbm\basic.py", line 3758, in __init__
    train_set.construct()
  File "c:\Users\Lenovo\AppData\Local\Programs\Python\Python310\lib\site-packages\lightgbm\basic.py", line 2574, in construct
    self._lazy_init(
  File "c:\Users\Lenovo\AppData\Local\Programs\Python\Python310\lib\site-packages\lightgbm\basic.py", line 2189, in _lazy_init
    self.set_label(label)
  File "c:\Users\Lenovo\AppData\Local\Programs\Python\Python310\lib\site-packages\lightgbm\basic.py", line 3097, in set_label
    self.set_field("label", label_array)
  File "c:\Users\Lenovo\AppData\Local\Programs\Python\Python310\lib\site-packages\lightgbm\basic.py", line 2860, in set_field
    _LIB.LGBM_DatasetSetField(
OSError: exception: access violation reading 0x0000000000000000


Please set a GitHub issue with above error message at: https://github.com/mljar/mljar-supervised/issues/new

