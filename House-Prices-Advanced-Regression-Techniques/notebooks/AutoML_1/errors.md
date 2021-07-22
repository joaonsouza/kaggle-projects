## Error for 4_Default_NeuralNetwork

[Errno 2] No such file or directory: 'AutoML_1\\4_Default_NeuralNetwork\\learner_fold_0.neural_network'
Traceback (most recent call last):
  File "C:\Users\u89391\Anaconda3\lib\site-packages\supervised\base_automl.py", line 1078, in _fit
    trained = self.train_model(params)
  File "C:\Users\u89391\Anaconda3\lib\site-packages\supervised\base_automl.py", line 365, in train_model
    mf.train(results_path, model_subpath)
  File "C:\Users\u89391\Anaconda3\lib\site-packages\supervised\model_framework.py", line 286, in train
    learner.save(p)
  File "C:\Users\u89391\Anaconda3\lib\site-packages\supervised\algorithms\sklearn.py", line 42, in save
    joblib.dump(self.model, model_file_path, compress=True)
  File "C:\Users\u89391\Anaconda3\lib\site-packages\joblib\numpy_pickle.py", line 475, in dump
    with _write_fileobject(filename, compress=(compress_method,
  File "C:\Users\u89391\Anaconda3\lib\site-packages\joblib\numpy_pickle_utils.py", line 175, in _write_fileobject
    file_instance = _COMPRESSORS['zlib'].compressor_file(
  File "C:\Users\u89391\Anaconda3\lib\site-packages\joblib\compressor.py", line 105, in compressor_file
    return self.fileobj_factory(fileobj, 'wb')
  File "C:\Users\u89391\Anaconda3\lib\site-packages\joblib\compressor.py", line 287, in __init__
    self._fp = io.open(filename, mode)
FileNotFoundError: [Errno 2] No such file or directory: 'AutoML_1\\4_Default_NeuralNetwork\\learner_fold_0.neural_network'


Please set a GitHub issue with above error message at: https://github.com/mljar/mljar-supervised/issues/new

