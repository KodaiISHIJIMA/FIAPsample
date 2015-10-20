# FIAPsample

"FIAPSample.unitypackage"をインポートして使ってください。
"Assets/fiap_demo.unity"を実行するとデモを見ることができます。
内容は、取得した電力によってオブジェクトの色が変化するというものです。
デモではI-REF棟6階照明装置全体Tの電力を取得しています。
Cubeの方は取得した値が前回よりも大きければ赤くなり、小さければ青くなります。
Sphereの方は取得した値が基準値よりも大きければ赤くなり、小さければ青くなります。
InspectorのTopicを変更すれば電力を取得する機器を変更できます。
Topicは"3dbcs.biz/UTokyo/iREF/6F/Hiloby/IEEE1888/Point/"にFIAPStorageのポイントIDをつなげたものになります。