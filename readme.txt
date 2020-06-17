分析に使うpythonのライブラリ(GPUは対応していません)を色々入れています。
jupyternotebookが自動的に起動するようになっています
ライブラリの順番を変えると特定のライブラリにおいて、動かなくなるバグがあるので（xgboostなど)気をつけて変更する必要があります。
How to use
docker run -p 127.0.0.1:8888:8888 -it --rm -v $(pwd):/notebooks akirtn/analysis_cpu_version
localhost:8888にアクセス