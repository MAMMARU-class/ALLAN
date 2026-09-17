# 参考になる opensource プロジェクト
- [openinterpreter/01](https://github.com/openinterpreter/01)  
rabbit の中身．基本構成はlivekit + agent  
現在ダウンロードできる personal ai assistant として 01 が存在する．  
面白いのはopeninterpreter.ただし，01に搭載されているのは古いversion．  
ESP32への実装コードも存在するので，**IoTへの応用の際にはかなり参考になる．**  

- [openinterpreter](https://github.com/openinterpreter)  
モデルに適した Harness を与える．"let the model drive the vehicle it's most confortable driving"．
ただし，モデルの切り替えは手動．  
高価なモデル(特にcodex)をできるだけ使わずに，安価なモデルの性能を最大限に引き出すことを目的としたプロジェクト．  
モデルに適した Harness Emulator を各 cloud LLM に渡すことで，特徴を生かしつつ，複雑なタスクをこなす．  
旧versionの01で使われていた時には harness は general であった．  


- [khoj](https://github.com/khoj-ai)


- [open-claw](https://github.com/openclaw)
複数のモデルを持つ．タスクの種類にモデルが対応している．  

- [open-jarvise](https://github.com/open-jarvis)
dynamic model routing を備える．タスクに応じて，複数のモデルを切り替える．  
